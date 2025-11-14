# 💻 TI de Bastidores — Plano de Comunicação do DITI (Prefeitura de Hortolândia)

Repositório institucional vinculado ao **Plano de Marketing Institucional** do **Departamento de Infraestrutura de TI (DITI)**.  
Seu objetivo é dar **visibilidade às ações, projetos e instrumentos de governança técnica** da área de TI da Prefeitura de Hortolândia, fortalecendo a imagem da tecnologia como eixo estratégico da gestão pública.

---

## 🎯 Objetivos

- **Dar visibilidade** às entregas de infraestrutura (rede, data center, segurança, continuidade).  
- **Educar** secretarias e servidores sobre boas práticas no uso de recursos tecnológicos.  
- **Fortalecer** a imagem institucional da TI como área estratégica do município.  
- **Alinhar** as comunicações internas e externas ao Planejamento Estratégico e à **LGPD**.  
- **Promover** a transparência e a rastreabilidade documental por meio do GitHub.

---

## 📁 Estrutura de Diretórios

A organização segue o padrão **Ano → Tipo → Documento**, com separação clara entre governança técnica, comunicação institucional e gestão documental.

```plaintext
ti-de-bastidores-comunicacao-hortolandia/
├── calendário-de-publicações/
│ └── 2025/
├── cartazes/
│ └── 2025/
├── memorandos-internos/
│ └── 2025/
│ ├── backup/
│ ├── rede/
│ └── segurança/
├── notícias/
│ └── 2025/
├── plano-marketing/
│ ├── plano_marketing_ti.md
│ └── README.md
├── slides/
│ └── 2025/
└── README.md


---

## 🧭 Integração dos Diretórios

🗂️ Integração dos Diretórios

| Diretório | Função Principal | Observações |
|-----------|------------------|-------------|
| 📁 **/plano-marketing/** | Documento-mãe `plano_marketing_ti.md`, contendo diretrizes, catálogos, KPIs e SLAs. | Núcleo estratégico e referência institucional. |
| 📨 **/memorandos-internos/** | Memorandos Internos (MIs) e instruções de TI. | Padrão obrigatório `MI-AAAA-XXX` com cabeçalho YAML. |
| 📊 **/slides/** | Apresentações institucionais e materiais visuais. | Base para relatórios bimestrais, sínteses e SEPLAN. |
| 📢 **/cartazes/** | Cartazes, campanhas e peças visuais. | Ligado à Identidade Visual e Engajamento Institucional. |
| 📰 **/notícias/** | Comunicados e notas internas. | Voltado à comunicação interna e transparência. |
| 🗓️ **/calendário-de-publicações/** | Agenda e planejamento de publicações. | Mantido pela comunicação da DITI. |



📘 *Essa estrutura modular permite à DITI manter separadas as camadas de gestão, comunicação e documentação técnica, garantindo clareza, rastreabilidade e evolução contínua.*

---

## 🧾 Padrão para Memorandos Internos (MI)

Os memorandos seguem a convenção:  
`MI-AAAA-XXX-titulo-kebab-case.md`

> **Exemplo:** `MI-2025-001-politica-uso-da-rede.md`

**Metadados obrigatórios (em formato YAML no topo do arquivo):**

```

id: MI-2025-001
assunto: Política de Uso da Rede
área: DITI
autor: Ailton Vendramini
data: 2025-11-10
estado: vigente
versão: 1.0
Fluxo de Aprovação

Etapa	Responsável
Redação inicial	DITI
Revisão técnica	Equipe de Infraestrutura (DITI)
Aprovação final	Diretor do DITI
Publicação	Responsável pelo Plano de Comunicação

🔗 Referências Normativas e Repositórios Relacionados
📘 Plano de Marketing Institucional do DITI

🧾 MI-2025-006 — Encaminhamento ao Diretor do DITI

🧠 Guia de Identidade Visual de TI (em desenvolvimento)

🔒 Política Municipal de LGPD e Segurança da Informação (a linkar quando disponível)

📞 Contato
Departamento de Infraestrutura de TI (DITI)
Prefeitura Municipal de Hortolândia
📧 suporte@hortolandia.sp.gov.br — ☎️ Ramal 5433

🧩 Atualizações Futuras
Publicação do Guia de Identidade Visual de TI.

Criação de modelos .pptx e .svg padronizados na pasta /slides/.

Expansão do dicionário técnico no plano de marketing.

Integração com o PDTI municipal e com o Plano de Transformação Digital.
