# Plataforma de Automação n8n

![Banner n8n](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

**Automação de Fluxo de Trabalho Segura para Equipes Técnicas**

O n8n é uma plataforma de automação de workflows que oferece às equipes técnicas a flexibilidade do código com a agilidade do *no-code*. Com mais de 400 integrações, capacidades nativas de IA e uma licença *fair-code*, o n8n permite construir automações poderosas mantendo o controle total sobre seus dados e implantações.

![Captura de Tela do n8n](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Capacidades Principais

*   **Desenvolvimento Híbrido:** Alterne sem esforço entre a construção visual baseada em nós e a escrita de código customizado em JavaScript/Python. Instale pacotes npm diretamente dentro dos workflows.
*   **Arquitetura Nativa de IA:** Construa workflows sofisticados de agentes de IA usando LangChain. Integre LLMs com suas fontes de dados privadas e modelos personalizados de forma segura.
*   **Flexibilidade de Implantação:** Hospede em sua própria infraestrutura (Docker, Kubernetes, npm) para máxima privacidade de dados ou utilize a oferta em nuvem gerenciada.
*   **Pronto para Empresas:** Recursos incluem permissões de usuário granulares, integração de SSO (Single Sign-On) e suporte para ambientes *air-gapped* (isolados).
*   **Ecossistema Vibrante:** Acesse mais de 400 integrações e 900+ modelos de workflows prontos para produção.

## Início Rápido

Comece a usar em segundos com `npx` (requer [Node.js](https://nodejs.org/)):

bash
npx n8n


Ou, preferencialmente, deploy usando Docker para um ambiente containerizado:

bash
# Crie um volume persistente
docker volume create n8n_data

# Execute o container
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n


Acesse o editor em `http://localhost:5678`.

## Documentação e Recursos

*   **[Documentação Oficial](https://docs.n8n.io):** Guias abrangentes e referências de API.
*   **[Diretório de Integrações](https://n8n.io/integrations):** Explore todos os conectores disponíveis.
*   **[Modelos de Workflow](https://n8n.io/workflows):** Importe projetos de automação prontos para uso.
*   **[Guia LangChain](https://docs.n8n.io/langchain/):** Aprofunde-se nas capacidades de IA.
*   **[Fórum da Comunidade](https://community.n8n.io):** Obtenha suporte e compartilhe conhecimento.

## Licenciamento

O n8n é distribuído sob a **[Licença de Uso Sustentável (Sustainable Use License)](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)** e a **[Licença Empresarial do n8n (n8n Enterprise License)](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md)**.

Este modelo "fair-code" garante:
*   **Disponibilidade do Código-fonte:** O código é sempre visível.
*   **Liberdade de Auto-hospedagem:** Implante o software em qualquer lugar.
*   **Extensibilidade:** Você pode criar e integrar seus próprios nós (*nodes*).

Suporte comercial e recursos empresariais estão disponíveis através da licença Enterprise. Consulte a [Documentação de Licenciamento](https://docs.n8n.io/reference/license/) para mais detalhes.

## Contribuições

Bem-vindos! Consulte nosso [Guia de Contribuição](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) para saber como relatar bugs, sugerir recursos e enviar *pull requests*.

## Carreiras

Interessado em moldar o futuro da automação? Visite nossa [Página de Carreiras](https://n8n.io/careers).

## Pronúncia

**n8n** significa "nodemation" (nodificação/automação de nós) e é pronunciado como "n-oito-n".