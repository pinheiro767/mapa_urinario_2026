# NeuroMapa Urinário — prompts de sprites e cenários

Os arquivos SVG incluídos no PWA já permitem jogar. Os prompts abaixo são opcionais para gerar uma edição visual mais cinematográfica, sem perder a identidade dos personagens. O layout usa **fundo azul-petróleo profundo, ciano, violeta e coral, painéis translúcidos e anatomia bem iluminada**.

## Direção de arte compartilhada

**Base para todos os prompts:** "Estilo anime original contemporâneo para universitários de Ciências Biológicas, visual novel 2.5D premium, pintura digital com iluminação cinematográfica volumétrica suave, anatomia humana didática precisa, cores equilibradas azul-petróleo, ciano-luminoso, violeta profundo e coral anatômico. Acabamento refinado, elegante, maduro e acolhedor, sem gore, sem personagem infantilizado, sem letras, sem marcas d'água e sem elementos copiados de franquias de anime. Áreas livres para sobrepor interface acessível."

## 1. Sprites dos três personagens (imagens separadas)

**Mika — investigadora:** "Sprite de personagem feminino de anime original, 22 anos, universitária de Ciências Biológicas, cabelos castanho-escuros longos com discretos reflexos violeta, olhos expressivos, jaqueta curta lilás sobre roupa casual, postura investigativa com tablet de anotações. Expressão curiosa e gentil, enquadramento 3/4 da cintura para cima, braços e mãos anatomicamente corretos, personagem isolada, fundo transparente, composição vertical 2:3, iluminação consistente. Produzir quatro variantes com mesmo rosto, roupa, proporções e paleta: curiosa, surpresa, pensativa e confiante."

**Dra. Yumi — docente clínica:** "Sprite de personagem feminino de anime original, docente médica e cientista de cerca de 38 anos, expressão inteligente e serena, cabelo escuro liso preso, jaleco branco sobre roupa azul-petróleo, crachá genérico sem texto, segurando tablet anatômico. Enquadramento cintura para cima 2:3, visual novel 2.5D, mãos anatomicamente corretas, fundo transparente. Variantes: explicando, questionando, satisfeita e preocupada. Preservar identidade exata entre cenas."

**Kai — estudante:** "Sprite de personagem masculino de anime original, cerca de 22 anos, cabelos curtos escuros levemente desalinhados, roupa casual azul e detalhes âmbar, rosto expressivo e amistoso, mochila discreta e caderno digital. Enquadramento cintura para cima 2:3, mãos anatômicas, fundo transparente. Variantes: hipótese, surpresa, dúvida e comemoração. Identidade visual consistente."

**Recomendação:** exportar um PNG/WebP transparente por personagem/expressão; base mínima 1024 × 1536 px. Não incluir balões de fala dentro das imagens: o PWA insere o diálogo por HTML para manter nitidez e acessibilidade.

## 2. Cenário principal: Laboratório do Sistema Urinário

"Sala futurista de Anatomia Humana em universidade, estética visual novel original, painéis holográficos translúcidos e mesa de estudo, ao centro uma projeção anatômica do sistema urinário humano completo com rins bilateralmente, artérias e veias renais, ureteres descendo à bexiga e uretra, topografia coerente, superfícies bem iluminadas, sem corpo humano realista exposto, elementos de tecnologia em ciano e lilás, ambiente científico acolhedor, composição 16:9 3840 × 2160 px. Nenhum personagem, texto, logotipo ou interface desenhada. Centro livre para superpor um mapa mental interativo."

## 3. Atlas do rim em corte

"Ilustração científica tridimensional estilizada em corte frontal de rim humano, alta precisão anatômica: cápsula fibrosa, córtex, colunas renais, pirâmides da medula, papilas, cálices menores, cálices maiores, pelve renal, seio renal, hilo, artéria e veia renais, ureter; cada estrutura com distinção cromática realista e acabamento de atlas premium. Objeto central, fundo transparente, sem legendas, sem texto, sem marcas, 4:3, 3000 × 2250 px. Não omitir as transições entre as partes coletoras; não inventar ductos." 

## 4. Atlas do ureter e três constrições

"Prancha anatômica 2.5D premium mostrando rim, pelve renal, ureter percorrendo o retroperitônio e cruzando a entrada da pelve até o segmento intramural da bexiga. Destacar visualmente, sem letras, as três regiões classicamente descritas como estreitamentos: junção pieloureteral, cruzamento com vasos ilíacos e junção ureterovesical/intramural. Proporções coerentes, sem duplicação de ureter, perspectiva anatômica respeitada. Fundo transparente, 4:3, precisão científica."

## 5. Atlas da bexiga e do trígono

"Bexiga urinária humana em secção anatômica didática, mucosa vesical com pregas, trígono vesical liso e triangular, dois óstios ureterais em posições superiores laterais, prega interuretérica, óstio interno da uretra inferior, colo vesical e continuidade uretral. Ureter direito e esquerdo chegando corretamente à parede posterolateral, iluminação coral suave, vista interna orientada, sem etiquetas e sem texto, fundo transparente, 4:3, ilustração universitária de altíssima fidelidade."

## 6. Atlas comparativo das uretras

"Duas pranchas anatômicas didáticas lado a lado, uma mostrando trajeto da uretra feminina da bexiga ao óstio externo no vestíbulo e a outra mostrando segmentos da uretra masculina: intramural, prostático, membranoso e esponjoso. Ilustração de ensino superior, secções sagitais esquemáticas discretas e corretamente proporcionadas, evitar detalhes externos desnecessários, fundo transparente, com espaço para legendas externas da interface, sem texto na imagem, proporção horizontal 16:9."

## 7. Fundo de vitória

"Fundo abstrato premium de conquista educacional, confetes delicados dourados, cianos e violetas, pequenas estrelas e medalhão holográfico neutro central, laboratório universitário desfocado, sem personagens, sem troféus esportivos, sem texto e sem números, 16:9, composição leve com espaços negativos para sobreposição de pontuação."

### Como substituir as imagens

O PWA usa SVGs em `assets/`. Os retratos aparecem como `assets/mika.svg`, `assets/yumi.svg` e `assets/kai.svg`, e as pranchas estão listadas em `app.js` (atributo `img` de cada ramo). É possível trocar os caminhos por arquivos WebP/PNG otimizados com os novos sprites. Para uso offline, inclua os novos arquivos na lista `CORE` de `sw.js`, aumente a versão de `CACHE` e publique novamente.
