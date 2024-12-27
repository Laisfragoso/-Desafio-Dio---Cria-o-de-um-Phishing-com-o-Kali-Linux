[# -Desafio-Dio---Cria-o-de-um-Phishing-com-o-Kali-Linux
Criação de um Phishing com o Kali Linux
Para criar um ataque de phishing com o setoolkit, siga estas etapas:

Instale o setoolkit no Kali Linux.
Inicie o setoolkit.
Selecione a opção 1 para criar um ataque de phishing.
Selecione o tipo de ataque que você deseja criar.
Configure o ataque.# Criação de Phishing com Kali Linux

Este repositório contém o passo a passo para a criação de um ataque de phishing educacional utilizando o Kali Linux e a ferramenta SETOOLKIT. 
**Este projeto é exclusivamente para fins educativos e deve ser usado de forma ética.**

---

## ⚙️ Ferramentas Utilizadas

- **Kali Linux** (Versão utilizada: 2024.4)
- **SETOOLKIT** (Social Engineering Toolkit)

---

## 🛠️ Configurando o Phishing no Kali Linux

### Passo a Passo - Linha de comando (terminal)

1. **Acesso root:**
   ```bash
   sudo su
   ```

2. **Iniciando o setoolkit:**
   ```bash
   setoolkit
   ```

3. **Selecionando o tipo de ataque:**
   - Escolha: `Social-Engineering Attacks`

4. **Selecionando o vetor de ataque:**
   - Escolha: `Web Site Attack Vectors`

5. **Selecionando o método de ataque:**
   - Escolha: `Credential Harvester Attack Method`

6. **Clonando o site alvo:**
   - Método: `site cloner`
   - Digite o endereço do site alvo para clonagem. Exemplo:
     ```bash
     https://www.instagram.com
     ```
     
---

## 📄 Resultados

Após executar os passos acima, as credenciais coletadas serão exibidas no terminal. Exemplo de saída:

```
POSSIBLE USERNAME FIELD FOUND:
POSSIBLE PASSWORD FIELD FOUND:
...
USERNAME: email_do_usuario@gmail.com
PASSWORD: senha_do_usuario
```
Para acesso ao printscreen do resultado [Clique Aqui](https://github.com/Vifernandestech/Fazendo-um-Phishing-com-Kali-Linux/blob/main/Resultado2Corte.PNG)
---

## ⚠️ Aviso de Ética

Este projeto é estritamente educacional e foi desenvolvido para promover o entendimento de táticas de engenharia social. O uso para fins maliciosos é **estritamente proibido** e pode acarretar consequências legais graves.

---

## 🔗 Referências

- [Documentação do SETOOLKIT](https://github.com/trustedsec/social-engineer-toolkit)
- [Kali Linux Official](https://www.kali.org/)

---

### Exemplos no GitHub
- [Repositório do Cassiano Peres - DIO](https://github.com/cassiano-dio/cibersecurity-desafio-phishing)

Envie o ataque.
Espere os resultados.
Limpe o setoolkit.
](https://github.com/Laisfragoso/-Desafio-Dio---Cria-o-de-um-Phishing-com-o-Kali-Linux/blob/main/README.md)
