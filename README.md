<div align="center">

# 🛡️ PASSWORD SECURITY & AI-ASSISTED PASSWORD CRACKING

### PASSWORD SECURITY • HASH ANALYSIS • JOHN THE RIPPER • HEXSTRIKE-AI • MCP

<img src="https://img.shields.io/badge/CYBERSECURITY-NETWORKWALKS-0A66C2?style=for-the-badge&logo=hackthebox&logoColor=white" />
<img src="https://img.shields.io/badge/WEEK%203-B084-6F42C1?style=for-the-badge" />
<img src="https://img.shields.io/badge/STATUS-COMPLETED-22C55E?style=for-the-badge" />
<img src="https://img.shields.io/badge/AUTHORIZED-YES-22C55E?style=for-the-badge" />

<br>

**W3-PS-AI | CYBERSECURITY | NETWORKWALKS**

### 👤 Nida Ibrahim Khedekar

**Cybersecurity Intern | Networkwalks Academy | Batch B084**

**Assessment Completed: November 2026**

---

</div>

# 🛡️ 1. Engagement Overview

| **Category**             | **Details**                                            |
| ------------------------ | ------------------------------------------------------ |
| 👤 **Student / Analyst** | Nida Ibrahim Khedekar                                  |
| 🎓 **Program / Batch**   | Networkwalks Cybersecurity Internship – B084           |
| 📅 **Assessment**        | November 2026                                          |
| 🧪 **Week**              | Week 03                                                |
| 🔐 **Primary Focus**     | Password Security & AI-Assisted Password Cracking      |
| ⚔️ **Module 01**         | Password Cracking with John the Ripper & Johnny        |
| 🌐 **Module 02**         | Password Cracking with Networkwalks Tools              |
| 🤖 **Module 03**         | HexStrike-AI MCP Server Setup with Claude Desktop      |
| 🧠 **Module 04**         | AI-Assisted Password Cracking using JTR + HexStrike-AI |
| 🖥️ **Platforms**        | Windows & Kali Linux                                   |
| 🔎 **Hash Format**       | PDF Hash (`$pdf$...`)                                  |
| 📚 **Wordlist**          | RockYou (`rockyou.txt`)                                |
| 🔗 **AI Integration**    | Model Context Protocol (MCP)                           |
| 📸 **Evidence**          | Practical Screenshots                                  |
| 🔐 **Authorization**     | Controlled Educational Laboratory                      |
| 📊 **Assessment Status** | Completed                                              |

---

# 🛡️ 2. Liability & Authorization Disclaimer

> **AUTHORIZED SECURITY TESTING ONLY**

All activities documented in this project were performed as part of an authorized cybersecurity educational laboratory provided by Networkwalks Academy.

The practical exercises involved password-security testing against the PDF files supplied for the training exercises.

The techniques demonstrated are intended strictly for:

* Cybersecurity education.
* Ethical hacking training.
* Password-security research.
* Authorized password-recovery exercises.
* AI-assisted security automation.
* Professional skill development.

Password-recovery techniques and security tools must only be used against files, systems, or environments for which appropriate authorization has been obtained.

Unauthorized password cracking, credential recovery, or access attempts may violate applicable laws and regulations.

**All tools and techniques documented in this repository must be used responsibly and within an explicitly authorized scope.**

> 🛡️ Security principle: Understand the target, define the scope, obtain authorization, execute responsibly, and document the results.

---

# 🛡️ 3. Introduction

This project documents the practical activities completed during **Week 3 of my Cybersecurity & Ethical Hacking internship with Networkwalks Academy**.

The week's activities focused on password security, PDF hash extraction, password recovery, John the Ripper, AI-assisted security testing, and MCP-based integration.

Unlike a conventional password-cracking exercise, this week's practical also introduced an AI-assisted approach using **HexStrike-AI MCP Server integrated with Claude Desktop**.

The assessment consisted of four practical modules.

### Practical Modules

```text
MODULE 01
John the Ripper + Johnny
        ↓
PDF Hash Extraction
        ↓
Password Recovery
        ↓
PDF Verification

MODULE 02
Networkwalks Hash Calculator
        ↓
Networkwalks Password Cracker
        ↓
Password Recovery
        ↓
PDF Verification

MODULE 03
HexStrike-AI MCP Server
        ↓
Claude Desktop Installation
        ↓
Python Virtual Environment
        ↓
Dependencies Installation
        ↓
MCP Configuration
        ↓
Server Integration

MODULE 04
AI-Assisted Password Cracking
        ↓
Claude Desktop
        ↓
HexStrike-AI MCP
        ↓
John the Ripper
        ↓
RockYou Wordlist
        ↓
Password Recovery
        ↓
PDF Verification
```

The exercises provided practical exposure to both traditional password-security tools and AI-assisted security automation.

---

# 🛡️ 4. Objectives

The primary objectives of the Week 3 practical were to:

* Understand password-security fundamentals.
* Understand PDF password protection and hash extraction.
* Install and configure John the Ripper.
* Configure and operate Johnny GUI.
* Extract PDF password hashes.
* Prepare hash files for password-recovery testing.
* Use Networkwalks Hash Calculator.
* Use Networkwalks Password Cracker.
* Understand the role of wordlists in password recovery.
* Explore the RockYou wordlist.
* Install and configure Claude Desktop on Kali Linux.
* Set up HexStrike-AI MCP Server.
* Create and configure a Python virtual environment.
* Install the required Python dependencies.
* Integrate HexStrike-AI with Claude Desktop through MCP.
* Verify John the Ripper availability through the AI-integrated environment.
* Perform AI-assisted password recovery.
* Understand AI-assisted security-tool orchestration.
* Capture practical evidence and document the results.

---

# 🛡️ 5. Tools & Technologies

| **Tool / Technology**         | **Purpose**                                                               |
| ----------------------------- | ------------------------------------------------------------------------- |
| Windows                       | Primary environment for Modules 01 and 02                                 |
| Kali Linux                    | Environment for Modules 03 and 04                                         |
| John the Ripper               | Password-security testing                                                 |
| Johnny GUI                    | Graphical interface for John the Ripper                                   |
| Claude Desktop                | AI desktop application                                                    |
| HexStrike-AI                  | AI-assisted cybersecurity tool orchestration                              |
| MCP                           | Communication protocol for connecting AI applications with external tools |
| Python 3                      | Runtime environment for HexStrike-AI                                      |
| Python Virtual Environment    | Isolated dependency management                                            |
| pip                           | Python package installation                                               |
| Git                           | Repository cloning                                                        |
| GitHub                        | Source code and project documentation                                     |
| RockYou Wordlist              | Password candidate dictionary                                             |
| Networkwalks Hash Calculator  | PDF hash extraction                                                       |
| Networkwalks Password Cracker | Browser-based password recovery                                           |
| Protected PDF                 | Authorized laboratory target                                              |
| Screenshots                   | Evidence collection                                                       |

---

# 🛡️ 6. Lab Architecture

The Week 3 assessment combined traditional password-recovery tools, browser-based utilities, and AI-assisted security automation.

```mermaid
flowchart TD

    A["📄 Authorized Protected PDF"] --> B["🔎 PDF Hash Extraction"]

    B --> C["#️⃣ PDF Hash"]

    C --> D["⚔️ JTR + Johnny"]
    C --> E["🌐 Networkwalks Tools"]
    C --> F["🤖 HexStrike-AI + Claude"]

    D --> G["🔓 Password Recovery"]
    E --> G
    F --> G

    H["🖥️ Kali Linux"] --> I["HexStrike-AI MCP Server"]
    I --> J["Claude Desktop"]
    J --> K["John the Ripper"]
    K --> L["📚 RockYou Wordlist"]
    L --> G

    G --> M["📄 PDF Verification"]
    M --> N["📸 Evidence Documentation"]

    style A fill:#0A66C2,color:#fff
    style B fill:#6F42C1,color:#fff
    style C fill:#238F89,color:#fff
    style D fill:#F59E0B,color:#fff
    style E fill:#0A66C2,color:#fff
    style F fill:#6F42C1,color:#fff
    style G fill:#22C55E,color:#fff
    style I fill:#C00000,color:#fff
    style J fill:#0A66C2,color:#fff
    style K fill:#238F89,color:#fff
    style L fill:#F59E0B,color:#fff
    style M fill:#22C55E,color:#fff
    style N fill:#404040,color:#fff
```
---
# 🛡️ 7. Module 01 – Password Cracking with John the Ripper & Johnny

## 7.1 Module Overview

The first module focused on using **John the Ripper (JTR)** and its graphical interface, Johnny, to recover the password of an authorized protected PDF.

John the Ripper is a password-security auditing tool capable of testing password candidates against supported password hashes.

Johnny provides a graphical interface that simplifies interaction with John the Ripper.

The practical involved obtaining the software, configuring Johnny, extracting the PDF hash, loading the hash file, initiating password recovery, and verifying the recovered password.

## 7.2 Module Environment

| **Component**   | **Details**              |
| --------------- | ------------------------ |
| Platform        | Windows PC               |
| Password Tool   | John the Ripper          |
| GUI             | Johnny                   |
| Target          | Authorized Protected PDF |
| Hash Extraction | PDF Hash Extractor       |
| Hash Format     | `$pdf$...`               |
| Hash File       | `hash1.txt`              |
| Verification    | Protected PDF            |

## 7.3 Module 01 Workflow

```mermaid
flowchart TD

    A["📥 Download John the Ripper"] --> B["🖥️ Install Johnny"]
    B --> C["⚙️ Configure john.exe"]
    C --> D["📄 Obtain Protected PDF"]
    D --> E["🔎 Extract PDF Hash"]
    E --> F["📝 Create hash1.txt"]
    F --> G["📂 Load Hash into Johnny"]
    G --> H["⚔️ Start New Attack"]
    H --> I["🔓 Recover Password"]
    I --> J["📄 Verify Protected PDF"]

    style A fill:#0A66C2,color:#fff
    style B fill:#F59E0B,color:#fff
    style C fill:#238F89,color:#fff
    style D fill:#C00000,color:#fff
    style E fill:#0A66C2,color:#fff
    style F fill:#238F89,color:#fff
    style G fill:#6F42C1,color:#fff
    style H fill:#C00000,color:#fff
    style I fill:#22C55E,color:#fff
    style J fill:#238F89,color:#fff
```

## 7.4 Practical Procedure

### 🔹 7.4.1 Download John the Ripper

John the Ripper was downloaded from its official distribution source.

Official website:

https://www.openwall.com/john/

### 🔹 7.4.2 Install Johnny GUI

Johnny was downloaded and installed on the Windows PC.

The graphical interface provided a convenient way to configure and operate John the Ripper.

### 🔹 7.4.3 Configure John the Ripper

The Johnny settings were opened.

The `john.exe` executable was located inside the JTR `run` directory and selected as the John the Ripper executable.

This established the connection between Johnny and the underlying JTR installation.

### 🔹 7.4.4 Obtain the Protected PDF

The PDF supplied with the Networkwalks practical exercise was downloaded and used as the authorized laboratory target.

### 🔹 7.4.5 Extract the PDF Hash

The PDF hash extractor was used to obtain the password-related hash from the protected PDF.

The extracted value followed the PDF hash format:

```text
$pdf$...
```

The hash was checked to ensure that unnecessary characters were not included.

### 🔹 7.4.6 Create the Hash File

The extracted hash was copied into Notepad and saved as:

```text
hash1.txt
```

The file was prepared in the required format for John the Ripper.

### 🔹 7.4.7 Load the Hash into Johnny

Johnny was opened and the **Open Password File** option was selected.

The previously created `hash1.txt` file was loaded.

### 🔹 7.4.8 Start the Password-Recovery Process

The **Start New Attack** option was selected.

John the Ripper began testing password candidates against the extracted PDF hash.

The recovery process demonstrated how password-auditing tools can identify weak or predictable passwords.

### 🔹 7.4.9 Verify the Recovered Password

The recovered password was entered into the protected PDF.

The PDF opened successfully, confirming the password-recovery result.

---
‎‎---

# 🛡️ 7. Module 01 Evidence

> Evidence screenshots are organized under:
>
> `module-1-jtr/evidence/`

### JTR / Johnny Setup

<img width="1365" height="720" alt="JTR Johnny Setup" src="https://github.com/user-attachments/assets/f88b54c2-db0d-4f43-805b-d841ccc90098" />

---

### 🔎 PDF Hash Extraction

<img width="1362" alt="PDF Hash Extraction 1" src="https://github.com/user-attachments/assets/ce9b58c9-d4f0-4ba0-a613-2dbd3a63c550" />

<img width="1363" alt="PDF Hash Extraction 2" src="https://github.com/user-attachments/assets/d55cce81-17da-4e78-bc38-79df96dc45d2" />

<img width="1365" alt="PDF Hash Extraction 3" src="https://github.com/user-attachments/assets/4d341891-9a24-4284-894d-3c5059ff30cd" />



---

### 📝 Hash File

<img width="1365" height="713" alt="Screenshot 2026-11-16 161702" src="https://github.com/user-attachments/assets/b3299b69-2f41-49ba-a043-637491e6f02b" />

<img width="1365" height="729" alt="Hash File Screenshot 2" src="https://github.com/user-attachments/assets/edd89c94-8b9f-4938-b65d-dd1958b9155b" />

<img width="1365" height="724" alt="Hash File Screenshot 3" src="https://github.com/user-attachments/assets/4cdc5081-85d1-4758-89af-08ea8e3164a6" />

---

### ⚔️ Password Recovery

<img width="1365" height="721" alt="Screenshot 2026-11-16 162441" src="https://github.com/user-attachments/assets/5271968f-a621-454f-a43e-dace6782608d" />

<img width="1365" height="724" alt="Screenshot 2026-11-16 162910" src="https://github.com/user-attachments/assets/70e6b41a-9fd7-4531-8413-d33ae42cea75" />

<img width="1365" height="727" alt="Screenshot 2026-11-16 163138" src="https://github.com/user-attachments/assets/7cfd7026-2cd5-4ae9-aca7-e704c87ed88a" />

---

# 🛡️ 8. Module 02 – Password Cracking with Networkwalks Tools

## 8.1 Module Overview

The second module introduced browser-based password-security tools developed by Networkwalks.

Unlike the first module, which used a locally installed password-recovery application, this exercise used two web-based tools:

* Networkwalks Hash Calculator.
* Networkwalks Password Cracker.

The practical demonstrated a browser-based workflow for extracting a PDF hash and performing password recovery.

## 8.2 Module Environment

| **Component** | **Details**                   |
| ------------- | ----------------------------- |
| Platform      | Windows Laptop                |
| Interface     | Web Browser                   |
| Hash Tool     | Networkwalks Hash Calculator  |
| Recovery Tool | Networkwalks Password Cracker |
| Target        | Authorized Protected PDF      |
| Hash Format   | `$pdf$...`                    |
| Verification  | Protected PDF                 |

## 8.3 Module 02 Workflow

```mermaid
flowchart LR

    A["📄 Protected PDF"] --> B["🌐 Hash Calculator"]
    B --> C["#️⃣ Extract PDF Hash"]
    C --> D["📋 Copy Complete Hash"]
    D --> E["⚔️ Password Cracker"]
    E --> F["⏳ Recovery Process"]
    F --> G["🔓 Recovered Password"]
    G --> H["📄 Open PDF"]
    H --> I["📸 Evidence"]

    style A fill:#C00000,color:#fff
    style B fill:#0A66C2,color:#fff
    style C fill:#238F89,color:#fff
    style D fill:#F59E0B,color:#fff
    style E fill:#C00000,color:#fff
    style F fill:#F59E0B,color:#fff
    style G fill:#22C55E,color:#fff
    style H fill:#238F89,color:#fff
    style I fill:#404040,color:#fff
```

## 8.4 Practical Procedure

### 🔹 8.4.1 Obtain the Protected PDF

The encrypted PDF supplied with the Networkwalks practical was downloaded.

### 🔹 8.4.2 Open Networkwalks Hash Calculator

The Hash Calculator was accessed through the web browser.

Tool:

https://networkwalks.com/hash-calculator/

### 🔹 8.4.3 Upload the PDF

The protected PDF was uploaded to the Hash Calculator.

The tool processed the document and generated the corresponding PDF hash.

### 🔹 8.4.4 Copy the Complete Hash

The complete hash value beginning with `$pdf$` was copied.

Ensuring that the entire hash was preserved was important for the next stage.

### 🔹 8.4.5 Open Networkwalks Password Cracker

The Password Cracker was opened in the browser.

Tool:

https://networkwalks.com/password-cracker/

### 🔹 8.4.6 Submit the Hash

The extracted PDF hash was pasted into the Password Cracker.

The password-recovery process was initiated.

### 🔹 8.4.7 Verify the Result

After the recovery process completed, the recovered password was entered into the protected PDF.

The document opened successfully, confirming the result.

---

# 🛡️ 9. Module 02 Evidence

> Evidence screenshots are organized under:
>
> `module-2-networkwalks-tools/evidence/`

### 🌐 Networkwalks Hash Calculator

<img width="1365" height="722" alt="Screenshot 2026-11-16 180933" src="https://github.com/user-attachments/assets/ae164b67-c58a-4d46-8bbb-af5a25bad853" />

<img width="1365" height="720" alt="Screenshot 2026-11-16 181026" src="https://github.com/user-attachments/assets/25c12843-793a-41c6-94ef-7778d10fdd67" />

<img width="1365" height="723" alt="Screenshot 2026-11-16 180909" src="https://github.com/user-attachments/assets/94b6400a-101a-4776-907a-96ced0fb3842" />

---

### ⚔️ Password Cracker

<img width="1365" height="729" alt="Screenshot 2026-11-16 180734" src="https://github.com/user-attachments/assets/2b6d250d-abbb-4f33-8f27-a2e91ac80d2c" />

<img width="1360" height="724" alt="Screenshot 2026-11-16 181053" src="https://github.com/user-attachments/assets/7d7fd847-af6b-4666-a99e-818371b460b7" />

<img width="1365" height="728" alt="Screenshot 2026-11-16 180515" src="https://github.com/user-attachments/assets/153f467b-7d66-4fd5-91db-38791de7d5d7" />

‎
---
# 🛡️ 9. Module 03 – HexStrike-AI MCP Integration & AI-Assisted Password Cracking with Claude Desktop

## 9.1 Module Overview

The third practical module extended the previous password-security exercises by introducing an **AI-assisted cybersecurity environment using HexStrike-AI MCP Server, Claude Desktop, and John the Ripper on Kali Linux**.

The objective was to configure HexStrike-AI, establish communication with Claude Desktop through the Model Context Protocol (MCP), and use the integrated environment to perform an authorized PDF password-recovery exercise.

The practical was divided into two connected stages:

**Stage 01 – Environment Setup and MCP Integration**

* Install Claude Desktop on Kali Linux.
* Clone and configure the HexStrike-AI repository.
* Create a Python virtual environment.
* Install the required dependencies.
* Start the HexStrike-AI server.
* Configure the MCP connection in Claude Desktop.

**Stage 02 – AI-Assisted Password Recovery**

* Verify John the Ripper availability through HexStrike-AI.
* Extract the hash from the supplied protected PDF.
* Use natural-language prompts through Claude Desktop.
* Perform dictionary-based password testing using the RockYou wordlist.
* Verify the recovered password by opening the protected PDF.

This exercise demonstrated how AI applications can interact with external cybersecurity tools through MCP integrations.

Unlike the previous modules, this practical introduced an additional layer of AI-assisted tool interaction, combining traditional password-auditing capabilities with an AI-powered interface.

---

## 9.2 Module Environment

| **Component**            | **Details**                    |
| ------------------------ | ------------------------------ |
| Operating System         | Kali Linux                     |
| AI Application           | Claude Desktop                 |
| MCP Framework            | Model Context Protocol (MCP)   |
| MCP Server               | HexStrike-AI                   |
| Repository               | `0x4m4/hexstrike-ai`           |
| Password Tool            | John the Ripper                |
| Programming Language     | Python 3                       |
| Dependency Manager       | pip                            |
| Environment              | Python Virtual Environment     |
| Wordlist                 | `rockyou.txt`                  |
| Target File              | `hash3.networkwalks_flag1.pdf` |
| Target Location          | `/home/kali/Desktop/`          |
| Hash Format              | PDF Hash                       |
| Server Address           | `http://localhost:8888`        |
| Server Port              | `8888`                         |
| MCP Script               | `hexstrike_mcp.py`             |
| Server Script            | `hexstrike_server.py`          |
| Password-Recovery Method | Dictionary-Based Testing       |
| Interaction Method       | Natural-Language Prompts       |
| Assessment Status        | Completed                      |

## 9.3 Module Architecture

The following architecture represents the complete workflow, from installing the required applications to recovering and verifying the protected PDF password.

```mermaid
flowchart TD

    A["🐉 Kali Linux Environment"]

    A --> B["📥 Install Claude Desktop"]
    A --> C["📥 Clone HexStrike-AI Repository"]

    C --> D["🐍 Create Python Virtual Environment"]
    D --> E["📦 Install Dependencies"]
    E --> F["🚀 Start HexStrike Server"]

    B --> G["⚙️ Configure MCP Settings"]
    F --> H["🌐 Local Server :8888"]

    G --> I["🔗 MCP Integration"]
    H --> I

    I --> J["🤖 Claude Desktop"]

    J --> K["🔍 Verify John the Ripper"]
    K --> L["📄 Analyze Protected PDF"]
    L --> M["#️⃣ Extract PDF Hash"]

    M --> N["📚 RockYou Wordlist"]
    N --> O["⚔️ John the Ripper"]
    O --> P["🔓 Password Recovery"]

    P --> Q["📄 PDF Verification"]
    Q --> R["📸 Evidence Documentation"]

    style A fill:#0A66C2,color:#fff
    style B fill:#6F42C1,color:#fff
    style C fill:#238F89,color:#fff
    style D fill:#F59E0B,color:#fff
    style E fill:#238F89,color:#fff
    style F fill:#C00000,color:#fff
    style G fill:#6F42C1,color:#fff
    style H fill:#0A66C2,color:#fff
    style I fill:#F59E0B,color:#fff
    style J fill:#22C55E,color:#fff
    style K fill:#238F89,color:#fff
    style L fill:#C00000,color:#fff
    style M fill:#0A66C2,color:#fff
    style N fill:#F59E0B,color:#fff
    style O fill:#6F42C1,color:#fff
    style P fill:#22C55E,color:#fff
    style Q fill:#238F89,color:#fff
    style R fill:#404040,color:#fff
```

---

## 9.4 Practical Procedure

### 🔹 9.4.1 Install Claude Desktop on Kali Linux

Claude Desktop was installed on Kali Linux using the Debian package repository provided by the Claude Desktop Debian project.

GitHub repository:

https://github.com/aaddrick/claude-desktop-debian

The installation involved adding the repository GPG key, configuring the package repository, updating package information, and installing Claude Desktop.

**Installation commands:**

```bash
# Add the GPG key
curl -fsSL https://pkg.claude-desktop-debian.dev/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/claude-desktop.gpg

# Add the repository
echo "deb [signed-by=/usr/share/keyrings/claude-desktop.gpg arch=amd64,arm64] https://pkg.claude-desktop-debian.dev stable main" | sudo tee /etc/apt/sources.list.d/claude-desktop.list

# Update package information
sudo apt update

# Install Claude Desktop
sudo apt install claude-desktop
```

### 🔹 9.4.2 Launch Claude Desktop

After installation, Claude Desktop was opened on Kali Linux.

The sign-in process was completed to access the application and prepare it for MCP integration.

### 🔹 9.4.3 Clone the HexStrike-AI Repository

The HexStrike-AI repository was obtained from GitHub.

Repository:

https://github.com/0x4m4/hexstrike-ai

The repository was cloned to the Kali Linux environment.

```bash
git clone https://github.com/0x4m4/hexstrike-ai.git

cd hexstrike-ai
```

### 🔹 9.4.4 Create a Python Virtual Environment

A dedicated Python virtual environment was created to isolate the dependencies required by HexStrike-AI.

```bash
python3 -m venv hexstrike-env
```

The environment was activated:

```bash
source hexstrike-env/bin/activate
```

Using a virtual environment helps maintain dependency isolation and reduces conflicts with system-managed Python packages.

### 🔹 9.4.5 Install Required Dependencies

After activating the virtual environment, the required Python dependencies were installed from the repository's requirements file.

```bash
pip3 install -r requirements.txt
```

This prepared the Python environment for the HexStrike-AI server and MCP integration.

### 🔹 9.4.6 Start the HexStrike-AI Server

After dependency installation, the repository directory was accessed and the virtual environment activated.

The HexStrike-AI server was launched.

```bash
cd ~/hexstrike-ai

source hexstrike-env/bin/activate

python3 hexstrike_server.py
```

The server was configured to run locally at:

```text
http://localhost:8888
```

This local server provided the communication endpoint required by the MCP integration.

### 🔹 9.4.7 Configure MCP Integration in Claude Desktop

The MCP server configuration was added to Claude Desktop.

**Configuration:**

```json
{
  "mcpServers": {
    "hexstrike-ai": {
      "command": "/home/kali/hexstrike-ai/hexstrike-env/bin/python",
      "args": [
        "/home/kali/hexstrike-ai/hexstrike_mcp.py",
        "--server",
        "http://localhost:8888"
      ]
    }
  }
}
```

The configuration specified:

* The Python interpreter inside the virtual environment.
* The HexStrike-AI MCP script.
* The local HexStrike server endpoint.
* The communication parameters required for integration.

This connected Claude Desktop with the HexStrike-AI MCP environment.

### 🔹 9.4.8 Verify John the Ripper Availability

After configuring the integration, Claude Desktop was used to interact with the HexStrike-AI environment.

The first natural-language prompt was:

```text
Check if John the Ripper is installed in this
HexStrike MCP and show me its version.
```

The objective was to check John the Ripper availability through the integrated environment.

### 🔹 9.4.9 Obtain the Protected PDF and Extract Its Hash

The target PDF supplied with the Networkwalks practical was copied to the Kali Linux desktop.

**Target filename:**

```text
hash3.networkwalks_flag1.pdf
```

**Target location:**

```text
/home/kali/Desktop/hash3.networkwalks_flag1.pdf
```

The following prompt was provided through Claude Desktop:

```text
Please calculate the hash value of this PDF file:

/home/kali/Desktop/hash3.networkwalks_flag1.pdf
```

The purpose was to obtain the PDF password hash required for the subsequent password-auditing exercise.

### 🔹 9.4.10 Initiate AI-Assisted Password Recovery

After obtaining the PDF hash, another natural-language prompt was submitted through Claude Desktop.

**Prompt used:**

```text
Please use JTR tool in this HexStrike MCP server
to crack the password of this PDF file.

Use the rockyou.txt wordlist dictionary.
```

Claude Desktop interacted with the HexStrike-AI MCP integration to initiate the John the Ripper password-recovery workflow.

This demonstrated how natural-language instructions can be used to interact with supported cybersecurity tools through an MCP-enabled environment.

### 🔹 9.4.11 Use the RockYou Wordlist

The RockYou wordlist was selected as the dictionary for the password-recovery exercise.

RockYou is a commonly referenced password wordlist used in cybersecurity education and authorized password-security assessments.

The commonly referenced Kali Linux location is:

```text
/usr/share/wordlists/rockyou.txt
```

Depending on the Kali Linux installation, the wordlist may initially be compressed.

The dictionary was used as the candidate-password source during the laboratory exercise.

### 🔹 9.4.12 Password Recovery and Verification

John the Ripper performed dictionary-based password testing against the extracted PDF hash.

The recovery process continued until a matching password was identified.

The recovered password was displayed through the AI-assisted workflow.

The recovered password was then entered into the protected PDF.

Successful access to the document confirmed the result of the password-recovery exercise.

---

## 9.5 AI Prompts Used

Natural-language prompts were used through Claude Desktop to interact with the HexStrike-AI MCP integration.

| **Stage** | **Prompt / Activity**                                                                | **Purpose**                               |
| --------- | ------------------------------------------------------------------------------------ | ----------------------------------------- |
| 01        | Check if John the Ripper is installed in this HexStrike MCP and show me its version. | Verify JTR availability                   |
| 02        | Calculate the hash value of the supplied PDF file.                                   | PDF hash extraction                       |
| 03        | Use JTR through HexStrike MCP to recover the PDF password.                           | Initiate password recovery                |
| 04        | Use the `rockyou.txt` wordlist dictionary.                                           | Specify the candidate-password dictionary |

The exercise demonstrated how an AI-assisted interface can simplify interaction with traditional cybersecurity tools.

---

## 9.6 Technical Workflow Summary

The complete practical followed this sequence:

```text
KALI LINUX ENVIRONMENT
          |
          v
CLAUDE DESKTOP INSTALLATION
          |
          v
HEXSTRIKE-AI REPOSITORY
          |
          v
PYTHON VIRTUAL ENVIRONMENT
          |
          v
DEPENDENCY INSTALLATION
          |
          v
HEXSTRIKE SERVER STARTUP
          |
          v
MCP CONFIGURATION
          |
          v
CLAUDE DESKTOP INTEGRATION
          |
          v
JOHN THE RIPPER AVAILABILITY CHECK
          |
          v
PDF HASH EXTRACTION
          |
          v
ROCKYOU WORDLIST SELECTION
          |
          v
AI-ASSISTED PASSWORD RECOVERY
          |
          v
PDF PASSWORD VERIFICATION
          |
          v
EVIDENCE DOCUMENTATION
```

---

## 9.7 Module 03 Evidence

> Evidence screenshots are organized under:
>
> `module-3-hexstrike-ai/evidence/`

### 🤖 Claude Desktop Installation

<img width="1365" height="720" alt="Screenshot 2026-11-17 174931" src="https://github.com/user-attachments/assets/8692742e-9059-4c4d-9b50-bcc2aad68a85" />

### 🐉 HexStrike-AI Repository Setup

<img width="1364" height="707" alt="Screenshot 2026-11-17 223454" src="https://github.com/user-attachments/assets/e2d11f15-d3d9-4461-ac29-e7292f8a7320" />

### 🔍 John the Ripper Availability Verification

<img width="1365" height="726" alt="Screenshot 2026-11-17 233546" src="https://github.com/user-attachments/assets/f9ee40cf-b677-4afa-83aa-a692fe2b6c2f" />

<img width="1365" height="715" alt="Screenshot 2026-11-17 233711" src="https://github.com/user-attachments/assets/1cb69eff-36b3-4796-9555-401ec9df8ba6" />

### #️⃣ PDF Hash Extraction

<img width="1365" height="714" alt="Screenshot 2026-11-17 234249" src="https://github.com/user-attachments/assets/2b7633a4-a557-4bbe-90b1-e2537c1bce6a" />

<img width="1365" height="721" alt="Screenshot 2026-11-17 234935" src="https://github.com/user-attachments/assets/607ebe7d-3c0c-486a-8352-a7be06bde706" />

<img width="1365" height="721" alt="Screenshot 2026-11-18 000104" src="https://github.com/user-attachments/assets/e9cee967-cedc-4607-ba2b-71eb1c074edd" />

### ⚔️ AI-Assisted Password Recovery

<img width="1365" height="719" alt="Screenshot 2026-11-17 234804" src="https://github.com/user-attachments/assets/67f4e864-7189-437a-af05-f54d8d57a569" />

<img width="1365" height="724" alt="Screenshot 2026-11-18 000006" src="https://github.com/user-attachments/assets/81bec1c2-394d-41cb-9ed6-017fc36a2299" />

<img width="1365" height="727" alt="Screenshot 2026-11-18 000400" src="https://github.com/user-attachments/assets/bb60dd4a-a529-43ca-b29b-0b59a764ccbe" />

### 🔓 Successful PDF Password Verification

<img width="1365" height="718" alt="Screenshot 2026-11-18 133556" src="https://github.com/user-attachments/assets/c1c08edb-e09b-47d8-be62-a180b7a98f36" />

<img width="1365" height="724" alt="Screenshot 2026-11-18 133457" src="https://github.com/user-attachments/assets/6c75390e-721e-42d3-a00c-378a42ec138f" />

<img width="1365" height="721" alt="Screenshot 2026-11-18 000540" src="https://github.com/user-attachments/assets/2e8ced4f-f4ad-4d01-adb9-f87e542983ee" />

---

# 🛡️ 12. Module Comparison

| **Category**    | **Module 01**      | **Module 02**          | **Module 03**  | **Module 04**        |
| --------------- | ------------------ | ---------------------- | -------------- | -------------------- |
| Primary Focus   | JTR & Johnny       | Browser-Based Recovery | MCP Setup      | AI-Assisted Recovery |
| Platform        | Windows            | Windows                | Kali Linux     | Kali Linux           |
| Main Tool       | John the Ripper    | Networkwalks Tools     | HexStrike-AI   | John the Ripper      |
| Interface       | Johnny GUI         | Web Browser            | Claude Desktop | Claude Desktop       |
| Hash Extraction | PDF Hash Extractor | Hash Calculator        | PDF Processing | HexStrike-AI         |
| Wordlist        | Not specified      | Tool-managed           | Not applicable | RockYou              |
| AI Integration  | No                 | No                     | Yes            | Yes                  |
| MCP             | No                 | No                     | Yes            | Yes                  |
| Result          | Completed          | Completed              | Configured     | Completed            |

## Results Summary

| **Assessment**                  | **Result**   |
| ------------------------------- | ------------ |
| JTR & Johnny Setup              | ✅ Completed  |
| PDF Hash Extraction             | ✅ Successful |
| Johnny Password Recovery        | ✅ Successful |
| Networkwalks Hash Calculator    | ✅ Completed  |
| Networkwalks Password Cracker   | ✅ Successful |
| Claude Desktop Installation     | ✅ Completed  |
| HexStrike-AI Repository Setup   | ✅ Completed  |
| Python Virtual Environment      | ✅ Configured |
| Dependency Installation         | ✅ Completed  |
| HexStrike Server Execution      | ✅ Completed  |
| MCP Configuration               | ✅ Completed  |
| Claude Desktop Integration      | ✅ Configured |
| JTR Version Verification        | ✅ Completed  |
| AI-Assisted PDF Hash Extraction | ✅ Completed  |
| RockYou Wordlist Usage          | ✅ Completed  |
| AI-Assisted Password Recovery   | ✅ Successful |
| PDF Verification                | ✅ Successful |

---

# 🛡️ 13. Password Security Concepts

## 13.1 Password Cracking

Password cracking refers to the process of recovering or identifying a password by testing candidate passwords against a stored password hash or protected-file authentication mechanism.

In cybersecurity, password-cracking tools are used for authorized security assessments to evaluate password strength.

## 13.2 Hashing

Hashing is a process that transforms input data into a derived representation known as a hash or message digest.

Cryptographic hash functions are generally designed to be one-way transformations.

In this practical, the extracted PDF hash served as the input for password-recovery testing.

**Important distinction:** A PDF password hash is an encoded representation of password-verification parameters. John the Ripper tests candidate passwords against those parameters; it does not simply reverse a hash.

## 13.3 Encryption vs Hashing

```text
ENCRYPTION

Plaintext
    ↓
Encryption
    ↓
Ciphertext
    ↓
Decryption with the correct key
    ↓
Plaintext


HASHING

Input
    ↓
Hash Function
    ↓
Hash / Digest
```

Encryption is designed to be reversible when the appropriate key is available.

Cryptographic hashing is generally designed as a one-way transformation.

The practical demonstrated how password-protected PDF files can be analyzed through authorized password-recovery techniques.

## 13.4 Dictionary Attack

A dictionary attack uses a collection of candidate passwords to test against a password hash.

The RockYou wordlist was used in the AI-assisted JTR practical.

The effectiveness of dictionary-based testing depends on whether the password appears in the selected wordlist and the characteristics of the target's password protection.

## 13.5 Wordlists

A wordlist is a collection of candidate passwords used during password-security testing.

Common wordlist locations in Kali Linux include:

```text
/usr/share/wordlists/
```

The RockYou wordlist is commonly used in educational password-auditing exercises.

## 13.6 Model Context Protocol (MCP)

Model Context Protocol is a standard that enables AI applications to communicate with external tools and data sources through defined interfaces.

In this practical, MCP was used to connect Claude Desktop with HexStrike-AI.

This allowed the AI application to interact with supported cybersecurity tools through the configured integration.

## 13.7 AI-Assisted Security Automation

AI-assisted security automation involves using an AI application to interpret instructions and interact with supported tools through integrations.

In this exercise:

```text
Natural Language Prompt
        ↓
Claude Desktop
        ↓
MCP Integration
        ↓
HexStrike-AI
        ↓
John the Ripper
        ↓
Password-Recovery Workflow
        ↓
Result
```

This demonstrated how AI can simplify interaction with security tools while still relying on the underlying technical capabilities of those tools.

---

# 🛡️ 14. Skills Demonstrated

<p align="center">

<img src="https://img.shields.io/badge/PASSWORD%20SECURITY-C00000?style=for-the-badge" />
<img src="https://img.shields.io/badge/HASH%20ANALYSIS-238F89?style=for-the-badge" />
<img src="https://img.shields.io/badge/JOHN%20THE%20RIPPER-0070C0?style=for-the-badge" />
<img src="https://img.shields.io/badge/JOHNNY-E87500?style=for-the-badge" />
<img src="https://img.shields.io/badge/HEXSTRIKE--AI-6F42C1?style=for-the-badge" />
<img src="https://img.shields.io/badge/MCP-INTEGRATION-0A66C2?style=for-the-badge" />
<img src="https://img.shields.io/badge/AI%20AUTOMATION-22C55E?style=for-the-badge" />
<img src="https://img.shields.io/badge/KALI%20LINUX-404040?style=for-the-badge" />

</p>

### Technical Skills

* Password-security testing.
* PDF hash extraction.
* John the Ripper.
* Johnny GUI.
* Dictionary-based password testing.
* RockYou wordlist.
* Networkwalks cybersecurity tools.
* Kali Linux.
* Claude Desktop installation.
* HexStrike-AI configuration.
* MCP integration.
* Python virtual environments.
* Python dependency management.
* Git and GitHub.
* AI-assisted security-tool interaction.
* Technical troubleshooting.
* Evidence collection.
* Professional technical documentation.

---

# 🛡️ 15. Observations & Technical Considerations

## Observation 01 – PDF Hash Format

The extracted PDF hash must be preserved correctly before being supplied to a password-recovery tool.

The `$pdf$` prefix identifies the PDF hash format used in this exercise.

Incomplete or incorrectly formatted hashes can cause password-recovery workflows to fail.

---

## Observation 02 – Password Complexity

Password-recovery duration depends on:

* Password length.
* Password complexity.
* Candidate search space.
* Wordlist contents.
* Hardware capabilities.
* Attack configuration.

Predictable passwords may be easier to recover using dictionary-based techniques.

---

## Observation 03 – Virtual Environment Management

Kali Linux uses an externally managed Python environment.

A dedicated virtual environment is useful for installing project-specific Python dependencies without modifying system-managed packages.

The HexStrike-AI practical introduced this approach through:

```bash
python3 -m venv hexstrike-env

source hexstrike-env/bin/activate
```

---

## Observation 04 – MCP Configuration

The MCP configuration requires the correct executable path, server script path, and local server address.

Incorrect paths or unavailable server processes can prevent successful communication between Claude Desktop and HexStrike-AI.

---

## Observation 05 – AI-Assisted Tool Interaction

The HexStrike-AI exercise demonstrated that natural-language prompts can be used to interact with supported cybersecurity tools through an MCP integration.

However, AI-assisted execution still depends on correct tool configuration, permissions, dependencies, and execution environments.

---

## Observation 06 – Wordlist Selection

The RockYou wordlist was used for dictionary-based password testing.

The practical demonstrated that wordlist selection is an important part of password-security testing.

A password that is absent from a particular wordlist may not be recovered through that dictionary-based attempt.

---

## Observation 07 – Evidence Collection

Cybersecurity documentation should demonstrate:

```text
What was performed
        ↓
How it was performed
        ↓
Which tools were used
        ↓
What was observed
        ↓
What the result demonstrated
        ↓
What security lessons were learned
```

This improves reproducibility, reviewability, and professional presentation.

---

# 🛡️ 16. Risk Analysis & Impact

| **#** | **Observation**                                     | **Security Relevance**                                  | **Potential Impact**                                    | **Risk**  |
| ----: | --------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------- | --------- |
|     1 | Weak password identified during authorized recovery | Demonstrates password predictability                    | Increased risk of unauthorized access                   | 🟠 Medium |
|     2 | Password hash available for testing                 | Hashes can be targeted for offline analysis             | Weak passwords may be recovered                         | 🟠 Medium |
|     3 | Dictionary-based testing                            | Common passwords can be identified efficiently          | Predictable credentials may be exposed                  | 🟠 Medium |
|     4 | AI-integrated security tools                        | AI can simplify security-tool interaction               | Misconfigured or unauthorized tool execution            | 🟠 Medium |
|     5 | MCP configuration                                   | External tools are exposed through defined integrations | Incorrect configuration may introduce security concerns | 🟠 Medium |
|     6 | Python dependency management                        | Project dependencies require isolation and maintenance  | Dependency conflicts or vulnerabilities                 | 🟠 Medium |
|     7 | Incomplete hash input                               | Accurate hash handling is essential                     | Recovery workflow may fail                              | 🟢 Low    |
|     8 | Wordlist limitations                                | Dictionary attacks depend on available candidates       | Password may remain unrecovered                         | 🟢 Low    |

> **Assessment Note:** These observations relate to the educational laboratory environment and do not represent vulnerabilities in unrelated production systems.

---

# 🛡️ 17. Security Recommendations

### 1. Use Strong Passwords

Use long, unique, and unpredictable passwords.

### 2. Avoid Password Reuse

Do not reuse the same password across multiple accounts or services.

### 3. Use Password Managers

Password managers help generate and securely store unique passwords.

### 4. Enable Multi-Factor Authentication

MFA provides an additional authentication layer beyond passwords.

### 5. Protect Password Hashes

Organizations should restrict access to password-related data and implement appropriate storage protections.

### 6. Use Modern Password-Storage Mechanisms

Use established password-hashing algorithms such as Argon2id, scrypt, or appropriately configured bcrypt.

### 7. Secure AI Integrations

MCP integrations should follow least-privilege principles and expose only the tools required for the intended workflow.

### 8. Maintain Python Environments

Use isolated virtual environments and keep dependencies updated.

### 9. Validate AI-Generated Actions

AI-assisted security operations should be reviewed and executed only within an authorized scope.

### 10. Document Security Assessments

Maintain clear evidence of procedures, observations, and outcomes.

---

# 🛡️ 18. Security Assessment Summary

| **Assessment Area**                  | **Status**  |
| ------------------------------------ | ----------- |
| Password Security Fundamentals       | ✅ Completed |
| PDF Hash Extraction                  | ✅ Completed |
| John the Ripper                      | ✅ Completed |
| Johnny Configuration                 | ✅ Completed |
| Networkwalks Hash Calculator         | ✅ Completed |
| Networkwalks Password Cracker        | ✅ Completed |
| Claude Desktop Installation          | ✅ Completed |
| HexStrike-AI Installation            | ✅ Completed |
| Python Virtual Environment           | ✅ Completed |
| Python Dependencies                  | ✅ Completed |
| MCP Server Configuration             | ✅ Completed |
| Claude Desktop Integration           | ✅ Completed |
| John the Ripper Version Verification | ✅ Completed |
| AI-Assisted Hash Extraction          | ✅ Completed |
| RockYou Wordlist Usage               | ✅ Completed |
| AI-Assisted Password Recovery        | ✅ Completed |
| PDF Verification                     | ✅ Completed |
| Evidence Collection                  | ✅ Completed |
| Technical Documentation              | ✅ Completed |

### Overall Practical Progress

```text
PASSWORD SECURITY          ████████████████████ 100% COMPLETED ✅

JTR / JOHNNY                ████████████████████ 100% COMPLETED ✅

NETWORKWALKS TOOLS           ████████████████████ 100% COMPLETED ✅

HEXSTRIKE-AI SETUP           ████████████████████ 100% COMPLETED ✅

CLAUDE DESKTOP + MCP         ████████████████████ 100% COMPLETED ✅

AI-ASSISTED PASSWORD CRACKING ████████████████████ 100% COMPLETED ✅

EVIDENCE & DOCUMENTATION     ████████████████████ 100% COMPLETED ✅
```

---

# 🛡️ 19. Key Learning Outcomes

Through the Week 3 practical exercises, I gained hands-on exposure to:

* Password-security fundamentals.
* PDF password protection.
* Hash extraction and analysis.
* John the Ripper.
* Johnny GUI.
* Networkwalks password-security tools.
* Dictionary-based password recovery.
* RockYou wordlist.
* Kali Linux security environment.
* Claude Desktop installation and configuration.
* HexStrike-AI MCP Server.
* Python virtual environment management.
* Python dependency installation.
* MCP-based AI integration.
* AI-assisted cybersecurity workflows.
* Security-tool orchestration.
* Technical troubleshooting.
* Evidence collection.
* Professional cybersecurity documentation.

### Learning Validation

The practical demonstrated the progression from conventional security-tool usage to AI-assisted cybersecurity workflows.

```text
SECURITY FUNDAMENTALS
        ↓
TRADITIONAL SECURITY TOOLS
        ↓
PRACTICAL EXECUTION
        ↓
AI INTEGRATION
        ↓
MCP CONFIGURATION
        ↓
AI-ASSISTED AUTOMATION
        ↓
RESULT VERIFICATION
        ↓
PROFESSIONAL DOCUMENTATION
```

One of the most valuable takeaways was understanding how AI applications can interact with external cybersecurity tools through MCP integrations.

This provided practical exposure to an emerging area of cybersecurity involving AI-assisted tool orchestration.

---

# 🛡️ 20. Conclusion

During **Week 3 of my Cybersecurity & Ethical Hacking internship at Networkwalks Academy**, I completed practical exercises covering password security, hash analysis, password recovery, AI integration, and security-tool automation.

The first module provided hands-on experience with **John the Ripper and Johnny**, including PDF hash extraction, hash-file preparation, password recovery, and verification.

The second module introduced the **Networkwalks Hash Calculator and Password Cracker**, demonstrating a browser-based approach to password recovery.

The third module extended the practical into AI-assisted cybersecurity by setting up **HexStrike-AI MCP Server with Claude Desktop on Kali Linux**.

This involved repository cloning, Python virtual environment creation, dependency installation, server execution, and MCP configuration.

The fourth module brought these components together by using **Claude Desktop, HexStrike-AI MCP, John the Ripper, and the RockYou wordlist** to perform an AI-assisted password-recovery exercise.

The overall practical progression was:

```text
PASSWORD SECURITY
        ↓
HASH ANALYSIS
        ↓
JOHN THE RIPPER
        ↓
NETWORKWALKS SECURITY TOOLS
        ↓
HEXSTRIKE-AI MCP SETUP
        ↓
CLAUDE DESKTOP INTEGRATION
        ↓
AI-ASSISTED PASSWORD RECOVERY
        ↓
VERIFICATION
        ↓
EVIDENCE & DOCUMENTATION
```

This week's exercises helped me understand not only how traditional password-security tools operate but also how AI applications can interact with external cybersecurity tools through MCP.

Most importantly, the practical reinforced the importance of understanding the underlying technology rather than relying entirely on automated tools.

**AI can assist with cybersecurity operations, but technical understanding, proper configuration, validation, and authorization remain essential.**

This project represents another step in my cybersecurity learning journey and contributes to my practical experience in password security, Kali Linux, security tooling, AI-assisted automation, and technical documentation.

---

# 🛡️ 21. Project Information

| **Project Detail**       | **Information**                                   |
| ------------------------ | ------------------------------------------------- |
| 👤 **Author**            | Nida Ibrahim Khedekar                             |
| 🏢 **Organization**      | Networkwalks Academy                              |
| 🎓 **Program**           | Cybersecurity & Ethical Hacking Internship        |
| 📅 **Week**              | Week 03                                           |
| 🎓 **Batch**             | B084                                              |
| 📆 **Assessment**        | November 2026                                     |
| 🔐 **Project Type**      | Authorized Cybersecurity Laboratory               |
| 🛡️ **Primary Focus**    | Password Security & AI-Assisted Password Cracking |
| ⚔️ **Module 01**         | John the Ripper & Johnny                          |
| 🌐 **Module 02**         | Networkwalks Hash Calculator & Password Cracker   |
| 🤖 **Module 03**         | HexStrike-AI MCP Server Setup                     |
| 🧠 **Module 04**         | AI-Assisted Password Cracking                     |
| 💻 **Platforms**         | Windows & Kali Linux                              |
| 🔗 **AI Application**    | Claude Desktop                                    |
| 🧰 **MCP Integration**   | HexStrike-AI                                      |
| 📚 **Wordlist**          | RockYou                                           |
| 📸 **Evidence**          | Practical Screenshots                             |
| 📊 **Assessment Status** | Completed                                         |

---

# 👤 22. Author

<div align="center">

### **Nida Ibrahim Khedekar**

**Cybersecurity Intern | Networkwalks Academy | Batch B084**

<br>

🛡️ **Cybersecurity & Ethical Hacking**

<br>

**Week 03 – Password Security & AI-Assisted Password Cracking**

<br>

**Learn • Practice • Analyze • Automate • Secure**

</div>

---

# 🛡️ 23. Assessment Progress

```text
PHASE 1
Password Security & JTR / Johnny
████████████████████████████████ COMPLETED ✅

PHASE 2
Networkwalks Password-Security Tools
████████████████████████████████ COMPLETED ✅

PHASE 3
HexStrike-AI MCP Server Setup
████████████████████████████████ COMPLETED ✅

PHASE 4
Claude Desktop Integration
████████████████████████████████ COMPLETED ✅

PHASE 5
AI-Assisted JTR Password Recovery
████████████████████████████████ COMPLETED ✅

PHASE 6
RockYou Wordlist & Verification
████████████████████████████████ COMPLETED ✅

PHASE 7
Evidence Collection & Documentation
████████████████████████████████ COMPLETED ✅
```

---

<div align="center">

### 🛡️ CYBERSECURITY • ETHICAL HACKING • AI-ASSISTED SECURITY

**Learn → Practice → Analyze → Automate → Document → Secure**

<br>

*W3-PS-AI | Networkwalks Academy | Batch B084 | November 2026*

<br>

**Nida Ibrahim Khedekar**

</div>

---
