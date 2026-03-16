# ⚔️ Brazil Phone OSINT v3.0

![Status](https://img.shields.io/badge/STATUS-OPERACIONAL-red?style=for-the-badge)
![Vibe](https://img.shields.io/badge/VIBE-KALI_LINUX-black?style=for-the-badge)

### 👊 Salve! 
Eu sou o jc. Sou iniciante na área, mas sou curioso pra caramba e viciado em entender como as coisas funcionam por baixo do capô. Este projeto aqui é meu "primeiro filho" no mundo da cibersegurança.

A ideia foi simples: **Por que ficar procurando números na mão se eu posso automatizar o Google pra fazer o trabalho sujo por mim?**

---

### 🕵️ O que esse script faz?
O **Brazil Phone OSINT** não é mágica, é **estratégia**. Ele pega um número de telefone e gera várias "Dorks" (comandos avançados do Google) para pescar:
- 📄 PDFs perdidos em servidores do governo ou empresas.
- 📊 Planilhas de Excel que alguém esqueceu de proteger.
- 📱 Perfis de redes sociais e cadastros antigos.

Tudo isso direto no terminal do Kali, com aquele visual **vermelho e preto** que a gente gosta.

---

### 🚀 Como testar a ferramenta (No seu Kali)
Se você também curte um terminal, é só colar esses comandos:

```bash
# Baixa o projeto
git clone [https://github.com/jcss191/brazil-phone-osint.git](https://github.com/jcss191/brazil-phone-osint.git)

# Entra na pasta
cd brazil-phone-osint

# Roda o motor de busca
python3 osint-phone.py
