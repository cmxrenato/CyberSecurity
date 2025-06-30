# CyberSecurity
Repositório para guardar toda a informação e projetos para a área de Segurança.


# Guia de Carreira em Segurança Cibernética e Compiladores  
## (Adaptado para Perfil Autista - Recife/PE)  

### 🎯 **Áreas com Pouca Concorrência**  
1. **Segurança Cibernética para Governo**  
   - Certificações: CEH (pentest), CISSP (gestão).  
   - Oportunidades: SERPRO, Porto Digital, Prefeitura de Recife.  

2. **Compiladores/Linguagens de Programação**  
   - Nicho: LLVM, CUDA (NVIDIA), otimização de código.  
   - Empresas: Intel, JetBrains, CESAR.  

### 💻 **Linguagens Prioritárias**  
- **Mínimo viável**: Python (automação), Bash (Linux), SQL (injection).  
- **Opcionais**: C/C++ (malware analysis), Ruby (Metasploit).  

### 📚 **Certificações**  
1. **CompTIA Security+** (Melhor para início)  
   - Cronograma: 6 semanas (vídeos do Professor Messer + TryHackMe).  
2. **CEH** (Foco em pentest/governo)  
   - Livro: "CEH v12 Study Guide" + laboratório com Kali Linux.  

### ✨ **Dicas para Autistas**  
- Foco em **certificações objetivas** (menos networking).  
- Peça **adaptações em provas** (tempo extra, ambiente silencioso).  
- Carreiras com **rotinas previsíveis**: análise forense, auditoria LGPD.  

### 🔗 **Links Úteis**  
- Cursos gratuitos: Cybrary, HTB Academy.  
- Simulados: ExamCompass (Security+), CEH da EC-Council. 



# Recursos para Aprender Python, Bash e SQL para Segurança da Informação

## 🐍 **Python para Segurança**

### 📚 Livros
1. **"Violent Python" (TJ O’Connor)**  
   - Foco: Automatizar pentests, exploração de redes  
   - Link: [Amazon](https://www.amazon.com.br/Violent-Python-Cookbook-Penetration-Engineers/dp/1597499579)

2. **"Black Hat Python" (Justin Seitz)**  
   - Foco: Criar ferramentas de hacking (sniffers, backdoors)  
   - Download gratuito: [GitHub](https://github.com/EbookFoundation/free-programming-books)

### 🎓 Cursos Gratuitos
- **HTB Academy - Python for Cybersecurity**  
  - Link: [HTB Academy](https://academy.hackthebox.com/)  
  - Prática: Scripts para varredura de portas

- **Automate the Boring Stuff with Python**  
  - Link: [Site Oficial](https://automatetheboringstuff.com/)  
  - Foco: Automação de tarefas

### 🛠️ Sites para Praticar
- **TryHackMe**: [Python Basics Room](https://tryhackme.com/room/pythonbasics)  
- **GitHub**: [Awesome Python Security](https://github.com/trustedsec/awesome-python-security)

---

## 💻 **Bash para Segurança**

### 📚 Livros
1. **"Linux Command Line and Shell Scripting Bible"**  
   - Foco: Comandos e scripts para análise forense

### 🎓 Cursos Gratuitos
- **Cybrary - Linux for Pentesters**  
  - Link: [Cybrary](https://www.cybrary.it/course/linux-for-pentesters/)  
  - Tópicos: `grep`, `awk`, `sed`

- **OverTheWire Bandit**  
  - Link: [Bandit Wargame](https://overthewire.org/wargames/bandit/)  
  - Jogo interativo de Bash

### 🛠️ Sites para Praticar
- **Command Challenge**: [cmdchallenge.com](https://cmdchallenge.com/)  
- **GitHub**: [Awesome Shell](https://github.com/alebcay/awesome-shell)

---

## 🗃️ **SQL para Segurança**

### 📚 Livros
1. **"The Web Application Hacker's Handbook"**  
   - Capítulos sobre SQL Injection

2. **"SQL Injection Attacks and Defense"**  
   - Foco: Exploração e prevenção

### 🎓 Cursos Gratuitos
- **TryHackMe - SQL Injection**  
  - Link: [THM Room](https://tryhackme.com/room/sqliro)

- **SQLZoo**  
  - Link: [sqlzoo.net](https://sqlzoo.net/)  
  - Exercícios interativos

### 🛠️ Sites para Praticar
- **DVWA**: Treinar SQL Injection localmente  
- **Hack The Box**: Máquinas como "Jerry"

---

## 🔧 **Projetos Práticos**

1. **Scanner de Portas (Python + Bash)**  
```python
import os
target = input("IP: ")
os.system(f"nmap -sV {target} | grep 'open' > ports.txt")
```

2. **Explorar SQL Injection no DVWA**

---

## 🎯 **Dicas para Autistas**
- Priorize materiais **textuais** e **exercícios práticos**  
- Use **Anki** para memorização: [Flashcards de Cybersecurity](https://ankiweb.net/shared/decks/cybersecurity)  
- Foque em **um tópico por vez** (ex: 1 semana = Python)

---

> **Para converter para PDF**:  
> - Use [StackEdit](https://stackedit.io/) (online)  
> - Ou `pandoc input.md -o output.pdf` (local)
