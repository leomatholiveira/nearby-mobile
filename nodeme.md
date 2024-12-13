Para Iniciar o projeto deve rodar o "npx i"
porque tem arquivos que não vão para o GIT
------------------------------------------------------------------------------------------------
npx create-expo-app@latest (VERSÃO)
---
Erro na Execução do NPX:
npx : O arquivo C:\Program Files (x86)\Nodejs\npx.ps1 não pode ser carregado porque a 
execução de scripts foi desabilitada neste sistema. Para obter mais informações, consulte 
about_Execution_Policies em https://go.microsoft.com/fwlink/?LinkID=135170.
No linha:1 caractere:1
+ npx expo start
+ ~~~
    + CategoryInfo          : ErrodeSegurança: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
	
	
No CMD deve digitar: Get-ExecutionPolicy
R: Caso esteja 'Restricted' deve então setar como Permitido.
Para isso digite:
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned

Depois executar novamente o 'npx expo start'
------------------------------------------------------------------------------------------------
Instalado packeds:
npx expo install expo-font @expo-google-fonts/rubik
npm install @tabler/icons-react-native
npx expo install react-native-svg
------------------------------------------------------------------------------------------------
Pasta API(Node):
Executar os comandos:
CMD: CD na pasta da API
CMD: npm i
CMD: npm start
------------------------------------------------------------------------------------------------
Instalar o pacote Axios
npm i axios
------------------------------------------------------------------------------------------------
Prisma Studio - Acessar a API de forma:
CMD: CD na pasta da API
CMD: npx prisma studio
Porque o backend tem o pacote do Prisma Studio para ficar melhor o visual e entendimento
------------------------------------------------------------------------------------------------
Instalar a Biblioteca do React Native Buttom Sheet (gorhom.dev/react-native-button-sheet/)
npm i @gorhom/button-sheet (por algum motivo tinha que ter o site aberto "https://gorhom.dev/react-native-bottom-sheet/")
------------------------------------------------------------------------------------------------
Instalar o Expo Maps:
npx expo install react-native-maps
npx expo install expo-location
Import:
import * as Location from "expo-location"
------------------------------------------------------------------------------------------------
Ler QRCode:
https://qrfy.com/pt
