# INTUNE – Analise de GPO

Você que esta migrando o gerenciamento de dispositivos para o INTUNE, considere utilizar a ferramenta que esta em preview de analise de GPO.
Basicamente voce exporta uma GPO do seu AD local e sobe ela aqui para saber se ela é compativel com seu ambiente INTUNE. Isso pode fazer toda a diferença na hora de planejar sua migração.

O que você vai precisar fazer é exportar suas GPOs do seu AD local e importa-las no analisador de GPO do INTUNE
https://cloudgeek.com.br/wp-content/uploads/2023/09/1.jpg

Após exportar, você utiliza esta tela abaixo para subir a GPO e deixar que a ferramenta lhe diga se ela é compativel ou não, para usar no INTUNE
https://cloudgeek.com.br/wp-content/uploads/2023/09/2.jpg

Abaixo segue a documentação oficial da Microsoft.

https://learn.microsoft.com/pt-br/mem/intune/configuration/group-policy-analytics

Abraço…
