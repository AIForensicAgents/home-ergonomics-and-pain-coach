flowchart LR
    A["📷 Camera Feed\n(Webcam / Phone)"] --> B["🦴 On-Device\nPose Estimation"]
    B --> C["🧠 Posture & Action\nClassification"]
    C --> D{"⚠️ Risk\nDetected?"}
    D -- Yes --> E["🔔 Gentle Alert\n+ Micro-Fix"]
    D -- No --> F["✅ Positive\nReinforcement"]
    E --> G["📋 Routine\nSuggestion"]
    F --> H["📊 Dashboard\nUpdate"]
    G --> H
    H --> I["📈 Trend Analysis\n& Recommendations"]

    style A fill:#E3F2FD,stroke:#1565C0,color:#0D47A1
    style B fill:#FFF3E0,stroke:#E65100,color:#BF360C
    style C fill:#F3E5F5,stroke:#6A1B9A,color:#4A148C
    style D fill:#FFF9C4,stroke:#F57F17,color:#E65100
    style E fill:#FFEBEE,stroke:#C62828,color:#B71C1C
    style F fill:#E8F5E9,stroke:#2E7D32,color:#1B5E20
    style G fill:#E0F7FA,stroke:#00695C,color:#004D40
    style H fill:#F5F5F5,stroke:#424242,color:#212121
    style I fill:#EDE7F6,stroke:#4527A0,color:#311B92