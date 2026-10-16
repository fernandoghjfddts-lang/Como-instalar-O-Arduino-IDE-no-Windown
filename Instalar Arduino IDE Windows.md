# Instalação do Arduino IDE no Windows

**Objetivo:** Instalar o Arduino IDE em um computador Windows

**Requisitos:** Computador com Windows 10/11

**Tempo estimado:** Entre 3 e 10 minutos

---

## Passo a Passo

1. **Baixando o Instalador:** 
Clique no link abaixo e o dowload do arquivo base da IDE vai começar imeditamente
<https://downloads.arduino.cc/arduino-ide/arduino-ide_latest_Windows_64bit.exe>

2. **Executando a Instalação**
  Após alguns segundos ou minutos o dowload será concluído e será possível acessá-lo nos arquivos do computador, ele provavelmente estará na forma 
**arduino-ide_2.3.10_Windows_64bit**

3. **Executando a Instalação:** 
 Clique 2 vezes no arquivo visível e você será automaticamente redirecionado para a seguinte página, a partir daí o processo é muito simples e seguir os comandos em destque na tela é suficiente para executar a instalação.
<img width="629" height="435" alt="image" src="https://github.com/user-attachments/assets/d7fe4d9b-fd40-44db-a979-89d8b899bbab" />
<img width="636" height="433" alt="image" src="https://github.com/user-attachments/assets/737fdb98-d134-415c-aac0-aeb4fdbb3ae0" />
Após a última imagem a instalação começará imediatamente e alguns segundos a IDE já estará instalada em seu computador, mas o Sparki ainda não pode se conectar com ela.


5. **Configurando a Placa:** 
   Já dentro da IDE, vá na aba **Arquivos**, no canto superior direito e depois **Preferências**, dentro de Preferências, vá até **URLs Adicionais para Gerenciadores de Placas** e cole o seguinte código:
   <https://raw.githubusercontent.com/ArcBotics/ArcBotics-Boards/master/package_arcbotics.com_boards_index.json>

---

## Possíveis Erros e Soluções
*   **Problema:** [Ex: "O computador não reconhece a placa na porta COM"]
*   **Solução:** [Ex: "Verifique se o cabo USB transmite dados ou instale o driver CH340 no link X."]
