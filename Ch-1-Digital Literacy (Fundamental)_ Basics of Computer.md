# Unit-1-Fundamentals of Computer / कंप्यूटर के मूल सिद्धांत

### What is Computer? Define Computer. / कंप्यूटर क्या है? कंप्यूटर को परिभाषित करें।

| English | हिंदी |
| :--- | :--- |
| Computer is an electronic device. | कंप्यूटर एक इलेक्ट्रॉनिक उपकरण है। |
| It takes data and instructions as input. | यह data और instructions को input के रूप में लेता है। |
| It processes the data according to the given instructions and gives information as output. | यह दिए गए निर्देशों के अनुसार data को process करता है और output के रूप में information देता है। |

---

### Block Diagram of Computer / कंप्यूटर का ब्लॉक डायग्राम

```text
                      +---------------------------------------+
                      |             Storage Unit              |
                      |  +---------------------------------+  |
                      |  |        Secondary Memory         |  |
                      |  |     (HDD, SSD, CD, DVD)         |  |
                      |  +---------------+-----------------+  |
                      |                  ^                    |
                      |                  |                    |
                      |                  v                    |
                      |  +---------------------------------+  |
                      |  |         Primary Memory          |  |
                      |  |          (RAM & ROM)            |  |
                      |  +---------------+-----------------+  |
                      +------------------|--------------------+
                                         |
                                         v
+---------------+      +-----------------+-----------------+      +---------------+
|  Input Unit   |----->|        Control Unit (CU)          |----->|  Output Unit  |
| (Keyboard,    | Data |-----------------------------------| Info |  (Monitor,    |
|    Mouse)     |      |   Arithmetic & Logic Unit (ALU)   |      |   Printer)    |
+---------------+      +-----------------------------------+      +---------------+
