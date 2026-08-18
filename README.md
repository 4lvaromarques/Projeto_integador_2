# Projeto_integador_2
Repositório para etapa 1


#  Rede de Murais Virtuais Escolares (RMVE)
> **Projeto Piloto:** Colégio Técnico de Bom Jesus (CTBJ) / UFPI


##  Sobre o Projeto
O **Mural Virtual de Projetos** é uma plataforma web open-source desenvolvida inicialmente para dar visibilidade aos trabalhos científicos, técnicos e artísticos dos alunos do **Colégio Técnico de Bom Jesus**. 

O grande diferencial deste ecossistema é a sua **arquitetura multi-institucional (SaaS Multi-tenant)**. Embora tenha nascido no CTBJ, o sistema foi projetado para que qualquer outra escola ou instituto técnico do Brasil possa criar sua própria instância e gerenciar seu próprio mural.

---

##  Funcionalidades Principais

###  Para o Colégio Técnico de Bom Jesus (E Escolas Parceiras)
*   **Feed de Projetos:** Visualização estilo "Pinterest" dos trabalhos com fotos, vídeos, resumos e links para o GitHub ou artigo PDF.
*   **Filtros Avançados:** Busca de projetos por Eixo Tecnológico (Ex: Agropecuária, Informática, Meio Ambiente), Ano Letivo e Orientador.
*   **Espaço Interativo:** Opção para a comunidade escolar deixar curtidas, comentários construtivos e compartilhar nas redes sociais.

###  Para a Expansão (Novas Instituições)
*   **Subdomínios Isolados:** Cada escola possui seu espaço único (Ex: `://muralescolar.com.br`, `://muralescolar.com.br`).
*   **Painel Administrativo Próprio:** Diretores e coordenadores gerenciam seus próprios alunos, professores e aprovações de projetos.
*   **Painel Geral de Redes:** Uma página central que exibe os projetos em destaque de todas as escolas cadastradas na federação.

---

##  Como Funciona a Arquitetura de Expansão


##  Tecnologias Sugeridas / Utilizadas

*   **Frontend:** [React.js](https://reactjs.org) / [Next.js](https://nextjs.org) (com Tailwind CSS para design responsivo).
*   **Backend:** [Node.js](https://nodejs.org) (Express) ou [Python](https://python.org) (FastAPI / Django).
*   **Banco de Dados:** [PostgreSQL](https://postgresql.org) (Ideal para isolamento de dados com Multi-tenancy).
*   **Armazenamento de Mídia:** AWS S3 ou Supabase Storage (Para as fotos dos projetos e feiras de ciências).

---





