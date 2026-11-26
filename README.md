# Conecta-Cidadão

Plataforma digital brasileira focada na dignidade laboral, conscientização e combate ao trabalho análogo à escravidão.

## 📂 Estrutura de Pastas

├── 📂 src/
│   └── 📄 index.html        # Código-fonte e interface mobile da plataforma
    └── 📄 input.css         # Cores criadas e comportamento das imagens
└── 📄 README.md             # Documentação e planejamento das Sprints

## ⏳ Cronograma de Desenvolvimento (Sprint 2)
Sprint 2: Interface Mobile, Formulário Sigiloso e Cards Informativos

    - Foco:Construir o visual da página inicial baseado no protótipo e estruturar a área de denúncias.

    - Cabeçalho e Banner Principal:Implementar o menu,a identidade visual institucional e a frase de impacto"Dignidade e Trabalho Decente para Todos".

    - Botão de Denúncia:Criar o botão de destaque vermelho"DENUNCIAR AGORA (Sigiloso)"direcionando para o formulário de relato anônimo.

    - Seção "g o Tema":Desenvolver os cards de"O que é Trabalho Escravo"e"Sinais de Alerta"com base no Artigo 149 do Código Penal.

## 🎨 Identidade Visual e Justificativa das Cores (`input.css`)

A paleta de cores da plataforma **Conecta-Cidadão** foi estruturada no arquivo `src/input.css` por meio da diretiva `@theme` do Tailwind CSS. A escolha tonal segue o padrão de design institucional brasileiro (`gov.br`), combinando sobriedade governamental, acessibilidade visual (alto contraste para leitura) e hierarquia semântica para orientar o cidadão:

* **Azul Institucional (`--color-gov-blue: #13315C` e `--color-gov-blue-hover: #0B2545`):** Cor predominante da identidade visual, escolhida por transmitir seriedade, confiança, segurança jurídica e respaldo oficial — elementos indispensáveis para uma plataforma voltada aos direitos trabalhistas e canais públicos de proteção. Além disso, oferece excelente contraste com tipografia branca.
* **Verde (`--color-gov-green: #009B3A`):** Representa a cidadania nacional, a proteção social e a promoção do trabalho decente (ODS 8), trazendo equilíbrio visual ao layout e destacando conteúdos educativos sobre direitos e prevenção.
* **Amarelo (`--color-gov-yellow: #FEDF00`):** Aplicado estrategicamente como cor de atenção preventiva e destaque gráfico, reforçando a identidade brasileira e sinalizando pontos de orientação e alerta sem gerar fadiga visual.
* **Vermelho de Urgência (`--color-gov-red: #D9251D` e `--color-gov-red-hover: #B01C15`):** Reservado exclusivamente para ações críticas e de denúncia (como o botão *"DENUNCIAR AGORA (Sigiloso)"* e ícones de risco grave), garantindo contraste imediato e facilitando que o usuário localize rapidamente o canal de socorro.
