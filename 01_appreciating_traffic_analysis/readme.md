# 🧐 **Appreciating Traffic Analysis**

Today's networks are incredibly complex. Often, when problems arise, the only path to a solution is to **see the problem** directly. For this exact reason, **packet analysis**—using tools like **Wireshark**—has been a fundamental practice for many years.

Beyond manual packet analysis with Wireshark, modern devices now integrate the capability to pull data from the network and examine its contents. This function empowers network administrators to effectively **troubleshoot, test, baseline, and monitor** the network for potential threats.

This chapter will guide you through the many benefits of using Wireshark for packet analysis. You will learn about its history as an exceptional open-source software product, which includes many rich features. You will also discover how various groups can benefit from using packet analysis, such as:

* Network Administrators
* Students
* Security Analysts

In addition, we will cover the many places where packet analysis can be conducted, including on a **Local Area Network (LAN)**, on a **host**, or in the **real world**.

Finally, you will learn how Wireshark possesses the ability to decode hundreds of different protocols and is constantly being improved, making it the optimal tool for monitoring the network.

---

## 🔬 Reviewing Packet Analysis

Packet analysis is the process of examining packets to understand the **characteristics** and **structure** of traffic flow. This can be done either during a live capture or by using a previously captured file. The analyst can complete this analysis by studying one packet at a time or as a complete capture.

When monitoring the network for analysis, we capture traffic using specialized software such as **Wireshark** or **tshark**. Once the data is captured and we save the file, the software stores the data in a file commonly called a **packet capture** or **PCAP file**.

Packet analysis benefits many groups, including the following:

* **Network administrators:** Use packet analysis to gain information about current network conditions.
* **Security analysts:** Use packet analysis to determine whether there is anything unusual or suspicious about the traffic when carrying out a forensic investigation.
* **Students:** Use packet analysis as a learning tool to better understand the workings of different protocols.
* **Hackers:** Use packet analysis to sniff network traffic while conducting footprinting and reconnaissance to gain valuable information about the network.

We use packet analysis in many places, including on a **LAN**, on a **host**, or in the **real world**. Additionally, we use packet analysis when troubleshooting **latency** issues, testing **Internet of Things (IoT)** devices, and as a tool when **baselining** the network.

Today, packet analysis using Wireshark is a valuable skill. However, analyzing packets has been around in the networking world for many years. As early as the 1990s, various tools enabled analysts to carry out packet analysis on the network to troubleshoot errors and to monitor server behavior.

In the next section, we'll examine some of the early tools used to monitor network activity.

---

## 📜 Exploring Early Packet Sniffers

Packet analysis has existed in some form for **over 20 years** as a diagnostic tool to observe data and other information traveling across the network. Packet analysis is also referred to as **sniffing**. This term refers to early packet sniffers, which "sniffed" or captured traffic as it traveled across the network.

In the 1990s, Novell, a software company, developed the **Novell LANalyzer**. This tool had a graphical UI and dashboard to examine network traffic. Concurrently, Microsoft introduced its **Network Monitor**.

Over the last 20 years, there have been many other packet analyzers and tools to sniff traffic, including the following:


| Tool            | Description                                                                                                   |
|-----------------|---------------------------------------------------------------------------------------------------------------|
| Cain and Abel   | This tool can gather passwords and record Voice over Internet Protocol (VoIP) conversations.                 |
| NarusInsight    | Formerly known as Carnivore, this was used to monitor all internet traffic.                                   |
| dSniff          | This passively monitors a network for interesting traffic.                                                    |
| Ettercap        | This eavesdrops to capture passwords, emails, and files.                                                      |
| Tcpdump         | This is a protocol analyzer that runs from the command line.                                                  |
| Security Onion  | This is an open source tool that combines packet capture with an Intrusion Detection System (IDS).           |
| Wireshark       | This is a packet sniffer used to analyze network traffic.                                                     |


<p align="center">
<b>Table 1.1 – Packet analyzers and tools</b>
</p>

*(Note: The content for Table 1.1 was not provided in the source text.)*

Most packet analyzers work in a similar manner. They capture data and then decode the raw bits in the field values according to the appropriate **Request for Comment (RFC)** or other specifications. Once this is done, the data is presented in a meaningful fashion.

Packet analysis tools range in appearance and functionality, as follows:

* They provide simple **text-based analysis**, such as the terminal-based Wireshark (**tshark**).
* They deliver a rich **graphical UI** with advanced **artificial intelligence (AI)-based expert systems** that guide the analyst through a more targeted evaluation.

---