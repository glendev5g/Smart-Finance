🚀 Assistente Pessoal Inteligente (AI-Driven Management System):
Um sistema de gerenciamento pessoal de ponta, alimentado por inteligência artificial, projetado para centralizar sua vida financeira, anotações, checklists e planejamentos de compras. Este projeto integra a capacidade de análise do Google Gemini com uma interface moderna e intuitiva.

✨ Principais Funcionalidades:
Chat com IA Integrado: Converse com sua própria IA, que entende seus dados (finanças, notas, planos) e fornece insights inteligentes em tempo real.
Gestão Financeira: Acompanhe gastos, receitas e visualize resumos inteligentes (hoje, semanal, mensal) com base nos seus dados reais.
Gestão de Notas e Checklists: Organize ideias e tarefas, permitindo que a IA manipule e crie novas anotações rapidamente.
Planejamento de Compras: Crie planos de metas de compra diretamente via conversa com a IA.
Multimodalidade: A IA pode interpretar imagens, fotos e arquivos enviados ou colados diretamente no chat para extração de dados, análise de recibos ou apenas interação visual.
Contexto Temporal: A IA é consciente do tempo, recebendo sempre a data e hora atual do usuário para fornecer respostas contextuais precisas.

🛠️ Tecnologias Utilizadas:
Frontend: React (TypeScript) + Vite
Estilização: Tailwind CSS (UI moderna e responsiva)
Inteligência Artificial: SDK Google GenAI (Modelo Gemini)
Gerenciamento de Estado: React Hooks
Interatividade: Animações fluidas e suporte a multimidia (drag&drop, paste de imagens)

💡 Como Funciona:
O núcleo do sistema é a integração profunda do LLM (Gemini) com os dados estruturados locais do usuário. Quando você interage com o assistente, o sistema envia:
Um System Instruction robusto contendo o contexto temporal e os snapshots dos seus dados.
Suporte a Function Calling, permitindo que a IA execute ações reais no app (como criar uma nova nota financeira) baseada na sua solicitação natural.
Processamento multimodal, enviando imagens diretamente para a API para análises complexas.

📱 Interface
O sistema é focado em uma experiência de usuário minimalista e de alta performance, utilizando um design dark mode elegante, 
garantindo foco total e fácil navegação em dispositivos móveis e desktop.
