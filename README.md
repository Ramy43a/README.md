# README.md
README.md
```mermaid
Flowchart TD
    subgraph المتغيرات الضابطة[المتغيرات الضابطة]
        A[حجم المنشأة]
        B[نوع الصناعة التحويلية]
        C[عمر المنشأة]
        D[الخبرة الإدارية]
    end

    E[التخطيط الاستراتيجي\n(المتغير المستقل)]
    F[الأداء التشغيلي\n(المتغير الوسيط)]
    G[الأداء المالي\n(المتغير التابع)]

    E -->|H1: تأثير إيجابي| F
    F -->|H2: تأثير إيجابي| G
    E -.->|H3: تأثير غير مباشر\n(وساطة الأداء التشغيلي)| G

    style E fill:#e6f2ff,stroke:#4682b4
    style F fill:#e6ffe6,stroke:#2e8b57
    style G fill:#fff2e6,stroke:#cd853f
    style المتغيرات الضابطة fill:#f2f2f2,stroke:#808080

