# 📍 GPS Escolar – Colégio Estadual Professora Silva Ferreira de Brito
Aplicativo web de navegação por voz para pessoas com deficiência visual, baseado na planta baixa do Colégio Estadual Professora Silva Ferreira de Brito (Ribeira do Pombal – BA).

✨ Funcionalidades

🎤 Reconhecimento de voz — fale o destino (ex: "sala de aula 3", "secretaria", "banheiro")
🔊 Navegação falada — instruções passo a passo em português brasileiro
🗺️ Mapa interativo — planta baixa da escola com destaque visual do local escolhido
📱 Mobile-first — otimizado para celular, com botões grandes e contraste alto
♿ Acessível — compatível com leitores de tela (ARIA), fonte Atkinson Hyperlegible
📴 PWA — pode ser instalado como app no celular (sem precisar da Play Store)
🔁 Botão "Ouvir Novamente" — repete as instruções quando necessário


🏫 Locais Mapeados
LocalBlocoSecretariaAdministrativoDiretoriaAdministrativoSala de ProfessoresAdministrativoLaboratório de InformáticaAdministrativoSala de VídeoAdministrativoSalas de Aula 01 a 11Sul / Leste / OesteBanheiros (acessíveis)CentralPátio DescobertoCentral

🚀 Como usar no GitHub Pages
1. Suba o repositório
bashgit init
git add .
git commit -m "GPS Escolar v1.0"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/gps-escola.git
git push -u origin main
2. Ative o GitHub Pages

Vá em Settings → Pages
Em Source, selecione Deploy from a branch → main → / (root)
Salve. Aguarde 1-2 minutos.
Acesse: https://SEU_USUARIO.github.io/gps-escola/


📱 Instalar como app no celular
Depois de abrir o site no navegador (Chrome/Edge):

Android: toque nos 3 pontinhos → "Adicionar à tela inicial"
iOS (Safari): toque no ícone de compartilhar → "Adicionar à Tela de Início"


🎤 Como usar

Abra o app no celular
Ouça a mensagem de boas-vindas
Toque no botão do microfone (círculo central) e diga o local desejado:

"sala de aula três"
"secretaria"
"banheiro"
"laboratório de informática"


O app irá falar as instruções e mostrar o local no mapa
Toque em "Ouvir Novamente" se precisar repetir

Você também pode tocar diretamente nos botões de destino na tela, sem usar a voz.

🛠️ Tecnologias

HTML5 + CSS3 + JavaScript (puro, sem framework)
Web Speech API — reconhecimento e síntese de voz
SVG — mapa vetorial interativo
PWA (Progressive Web App) — manifest.json


🌐 Compatibilidade
NavegadorReconhecimento de VozSíntese de VozChrome (Android)✅✅Edge (Android)✅✅Samsung Internet✅✅Firefox❌✅Safari (iOS)✅✅

Recomendado: Google Chrome no Android para melhor experiência de voz.


♿ Acessibilidade

Fonte Atkinson Hyperlegible — projetada para pessoas com baixa visão
Alto contraste (fundo escuro + texto claro + verde brilhante)
Todos os botões com aria-label descritivo
aria-live regions para anúncios dinâmicos
Botões com tamanho mínimo de 100px (fácil de tocar)
Compatible com TalkBack (Android) e VoiceOver (iOS)


📐 Base
Planta baixa do Colégio Estadual Professora Silva Ferreira de Brito
Rua João Fernandes Gama – Ribeira do Pombal, BA
Projeto: GBM Engenharia e Arquitetura | SEC-COINF / SUPEC

📄 Licença
MIT — livre para uso educacional e adaptação.
