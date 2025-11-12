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


'''ti-de-bastidores-comunicacao-hortolandia/
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

yaml
Copiar código

---

## 🧭 Integração dos Diretórios

| Diretório | Função Principal | Observações |
|------------|------------------|--------------|
| **/plano-marketing/** | Contém o documento-mãe `plano_marketing_ti.md`, que consolida diretrizes, catálogos e SLAs. | É o núcleo estratégico do projeto e o principal documento institucional. |
| **/memorandos-internos/** | Reúne comunicações formais (MIs) e instruções vinculadas à execução do plano. | Deve seguir o padrão `MI-AAAA-XXX` com cabeçalho YAML. |
| **/slides/** | Abriga apresentações institucionais e materiais visuais de apoio. | Usado para relatórios bimestrais, sínteses executivas e apresentações à SEPLAN. |
| **/cartazes/** | Contém campanhas visuais e comunicados públicos. | Ligado à Identidade Visual e Engajamento Institucional. |
| **/notícias/** | Armazena comunicados e notas internas. | Voltado à comunicação entre equipes e à transparência de resultados. |
| **/calendário-de-publicações/** | Agenda e planeja os marcos de comunicação e divulgação. | Mantido pela equipe de comunicação da DITI. |

📘 *Essa estrutura modular permite à DITI manter separadas as camadas de gestão, comunicação e documentação técnica, garantindo clareza, rastreabilidade e evolução contínua.*

---

## 🧾 Padrão para Memorandos Internos (MI)

Os memorandos seguem a convenção:  
`MI-AAAA-XXX-titulo-kebab-case.md`

> **Exemplo:** `MI-2025-001-politica-uso-da-rede.md`

**Metadados obrigatórios (em formato YAML no topo do arquivo):**

```yaml
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
