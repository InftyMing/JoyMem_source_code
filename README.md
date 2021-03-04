# JoyMem_source_code
本项目题为JoyMem: A Password Generation Mechanism Based on Interleaved Security Structure and Q&A Design，
即一个基于安全性交替结构和问答机制的口令生成器。主要内容是（以下内容选自本项目论文摘要）：
Abstract—It is well known that common users tend to exploit personally identifiable information and reuse passwords to construct new passwords, rendering their accounts at high risks. As a countermeasure, tools like password managers (PMs) and password generation mechanisms (PGMs) are employed to help users securely manage passwords. PMs can manage and generate random (and thus secure) passwords, but most existing PMs are subject to serious security loopholes, and users also express wide privacy concerns, leading to low popularity. Relatively, PGMs have been more widely used, but most existing PGMs fail to well balance security and usability. To get out of these dilemmas, we propose a new PGM, called JoyMem, which can generate passwords with sufficient security and acceptable usability. We domonstrate its effectiveness through both theoretical analysis and experiments, and compare it with leading PGMs, such as Surpass, Optiwords and MenGenEx/MnePerEx. Unlike most existing PGMs that are only suitable for a single-language, JoyMem has much better scalability and can be deployed on websites of different languages or services. We give its detailed constructions in both Chinese and English in this paper. To improve password memorability, we make the passwords generated by JoyMem satisfy Interleaved Security Structure (ISS) of user-constructed passwords, but have significantly more interleaved layers and high-security parts generated by Long Short-Term Memory. ISS means that, a high-security part and a low-security part are arranged alternately, and the former and the subsequent latter form an interleaved layer, and vice versa. To resist targeted attacks, inspired by human memory laws, we design a Question and Answer (Q&A) mechanism to collect users’ insensitive and unspecific personal information. This information forms the mnemonic parts (i.e., low-security parts) after a series of operations, including keyword extraction, synonym association and Markov segmentation. It is worth noting that our Q&A design can guarantee the probability regression of the question selection and the uniform distribution of the answer space. This overcomes the shortcomings of existing PGMs based on the Q&A mechanism (e.g., Cognitive passwords and Associative passwords).

项目介绍、论文相关数据集、源码请参见链接https://github.com/JoyMem
[注]：此链接为项目组提交论文时用于存放所有项目相关内容的库，所有内容均由本项目组成员完成。

指导老师：南开大学 贾春福教授、南开大学 汪定教授、南开大学 密码学实验室 董奇颖博士

项目组成员：南开大学 计算机学院 孙铭(1711377)、南开大学 网络空间安全学院 徐晖宇(1713666)、南开大学 网络空间安全学院 段逸赫(1811351)

辅助完成：南开大学 网络空间安全学院 段非、南开大学 网络空间安全学院 单轩、南开大学 网络空间安全学院 洪淑宏
