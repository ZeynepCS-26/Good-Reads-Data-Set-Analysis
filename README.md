```mermaid
flowchart LR
    A[(Goodreads Veri Seti)] --> B[Veri Temizleme & Ön İşleme]
    B --> C{"K-Nearest Neighbors (KNN)"}
    C -->|Yazar & Tarih Ağırlıkları| D[Mesafe & Benzerlik Hesaplama]
    D --> E(["🎯 Kullanıcıya Özel Kitap Önerisi"])
    
    style A fill:#2c3e50,stroke:#f39c12,stroke-width:2px,color:#fff
    style B fill:#34495e,stroke:#bdc3c7,stroke-width:2px,color:#fff
    style C fill:#2980b9,stroke:#3498db,stroke-width:2px,color:#fff
    style D fill:#34495e,stroke:#bdc3c7,stroke-width:2px,color:#fff
    style E fill:#27ae60,stroke:#2ecc71,stroke-width:2px,color:#fff
