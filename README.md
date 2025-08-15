# 🎯 Simulação de Phishing com Kali Linux (Projeto Educacional)

> ⚠️ **Aviso Legal:** Este projeto é destinado exclusivamente para fins **educacionais e de conscientização em segurança da informação**. Nenhuma atividade descrita aqui deve ser realizada fora de ambientes controlados e autorizados. O uso indevido pode violar leis locais e os termos de uso de plataformas.

---

## 🛠 Ferramentas Utilizadas

- [Kali Linux](https://www.kali.org/)
- [Setoolkit (Social-Engineer Toolkit)](https://github.com/trustedsec/social-engineer-toolkit)

---

## 🧪 Ambiente de Teste Recomendado

- Máquina virtual (ex: VirtualBox ou VMware)
- Rede local isolada (sem acesso à internet)
- Página de teste própria (ex: `http://test.local`) ou servidor local

---

## 🚀 Passo a Passo: Simulação de Phishing

1. **Acesso root**
   ```bash```
   ```sudo su```
---
2. Iniciar o Setoolkit c
  ```bash```
    ```setoolkit```
 
---
3. 	Selecionar tipo de ataque
  - 1) Social-Engineering Attacks
       
---
4. 	Escolher vetor de ataque
   - 2) Website Attack Vectors

----
5. 	Método de coleta de credenciais
  - 3) Credential Harvester Attack Method
       
---
6. 	Clonar site de teste
  - 2) Site Cloner
  - Inserir URL de teste: http://test.local
    
---
7. 	Obter IP da máquina
  ```bash```
  ```ifconfig```
---
8. Acessar página clonada
- Em outro dispositivo da rede local, acessar: *http://<IP-da-máquina>*

---
📊 Resultados Esperados
- Credenciais inseridas na página de teste serão registradas em:
  
```bash```

```/var/www/html```
- Logs podem ser visualizados diretamente no terminal ou no arquivo gerado pelo Setoolkit.


![Alt text](./passwd.png "Optional title")

---
📚 Referências e Recurso
- [Kali Linux](https://www.kali.org/)
- [Setoolkit (Social-Engineer Toolkit)](https://github.com/trustedsec/social-engineer-toolkit)
- [OWASP - Phishing](https://owasp.org/www-chapter-dorset/assets/presentations/2020-04/RT_OSINT_Phishing.pdf)

✅ Boas Práticas
- Nunca use este projeto em redes públicas ou com sites reais.
- Sempre informe e obtenha consentimento dos envolvidos em testes.
- Use ambientes virtuais e isolados para simulações
