# Unit-1-Fundamentals of Computer / कंप्यूटर के मूल सिद्धांत

### What is Computer? Define Computer. / कंप्यूटर क्या है? कंप्यूटर को परिभाषित करें।

| English | हिंदी |
| :--- | :--- |
| Computer is an electronic device. | कंप्यूटर एक इलेक्ट्रॉनिक उपकरण है। |
| It takes data and instructions as input. | यह data और instructions को input के रूप में लेता है। |
| It processes the data according to the given instructions and gives information as output. | यह दिए गए निर्देशों के अनुसार data को process करता है और output के रूप में information देता है। |

---

### Block Diagram of Computer / कंप्यूटर का ब्लॉक डायग्राम

```mermaid
flowchart LR
    Input([Input Unit<br>Keyboard, Mouse]) -- Data --> CPU

    subgraph CPU_Block [CPU - Central Processing Unit]
        direction TB
        CU[Control Unit]
        ALU[Arithmetic & Logic Unit]
    end

    subgraph Memory_Block [Storage Unit]
        direction TB
        PM[Primary Memory<br>RAM & ROM]
        SM[Secondary Memory<br>HDD, SSD, CD]
    end

    CPU_Block <-->|Store / Retrieve| Memory_Block
    CPU -- Information --> Output([Output Unit<br>Monitor, Printer])
    
    style Input fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    style Output fill:#e1f5fe,stroke:#01579b,stroke-width:2px
    style CPU_Block fill:#fff3e0,stroke:#e65100,stroke-width:2px
    style Memory_Block fill:#f3e5f5,stroke:#4a148c,stroke-width:2px
