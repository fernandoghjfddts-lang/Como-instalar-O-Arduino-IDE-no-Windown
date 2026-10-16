# Instalação do Arduino IDE no Windows

**Objetivo:** Instalar o Arduino IDE em um computador Windows

**Requisitos:** Computador com Windows 10/11, um robô Sparki

**Tempo estimado:** Entre 3 e 10 minutos

---

## Passo a Passo

1. **Baixando o Instalador:** 
Clique no link abaixo e o dowload do arquivo base da IDE vai começar imeditamente
<https://downloads.arduino.cc/arduino-1.8.19-windows.exe>

3. **Executando a Instalação**
  Após alguns segundos ou minutos o dowload será concluído e será possível acessá-lo nos arquivos do computador, ele provavelmente estará na forma 
**arduino-1.8.19-windows**

4. **Executando a Instalação:** 
 Clique 2 vezes no arquivo visível e você será automaticamente redirecionado para a seguinte página, a partir daí o processo é muito simples e seguir os comandos em destque na tela é suficiente para executar a instalação.
<img width="629" height="435" alt="image" src="https://github.com/user-attachments/assets/d7fe4d9b-fd40-44db-a979-89d8b899bbab" />
<img width="636" height="433" alt="image" src="https://github.com/user-attachments/assets/737fdb98-d134-415c-aac0-aeb4fdbb3ae0" />
<img width="634" height="436" alt="image" src="https://github.com/user-attachments/assets/8efa95fd-4236-490b-aa1d-4af7eeaa1fa8" />

Após a última imagem a instalação começará imediatamente e alguns segundos a IDE já estará instalada em seu computador, mas o Sparki ainda não pode se conectar com ela.


4. **Configurando a Placa:** 
   Já dentro da IDE, vá na aba **Arquivos**, no canto superior direito e depois **Preferências**, dentro de Preferências, vá até **URLs Adicionais para Gerenciadores de Placas** e cole o seguinte código:
   <https://raw.githubusercontent.com/ArcBotics/ArcBotics-Boards/master/package_arcbotics.com_boards_index.json>

   <img width="1064" height="642" alt="image" src="https://github.com/user-attachments/assets/846bcce5-7b6e-4d24-abf1-5ad2f3795377" />

   Após isso, conecte o cabo USB no sparki e no computador para que ele fique utilizável e vá até a aba **Ferramentas**, depois **Placa** e **Gerenciador de Placas**, lá pesquise por **Sparki** e instale a Placa

   <img width="1113" height="728" alt="image" src="https://github.com/user-attachments/assets/f0185a48-6af6-41ed-a7c8-5a01dc741090" />

   <img width="1159" height="251" alt="image" src="https://github.com/user-attachments/assets/7fff8358-db85-49ac-942b-4374d31b6a2e" />

   

   Após esse processo, o seu computador estará concectado com o Sparki e pronto para ser usado, basta selecionar a porta conectada ao USB e a placa que tem como nome ArcBotics Sparki.
   




---

## Possíveis Erros e Soluções
*   **Problema:** [Ex: "O computador não reconhece a placa na porta COM"}
*   **Solução:** [Ex: "Verifique se o cabo USB transmite dados ou instale o driver CH340 no link X."]
