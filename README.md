# Trabalho 1 - Changelog e Release com GitHub Actions

**Integrantes da Dupla:**
* James Soares Silva (RA: 250380)

## Descrição do Projeto
Este repositório foi criado para demonstrar o uso e o funcionamento de fluxos de CI/CD utilizando o **GitHub Actions**. O projeto implementa duas automações independentes: a primeira é responsável por manter um registro atualizado das alterações do código (Changelog), e a segunda automatiza o empacotamento e a publicação de versões do projeto (Release).

### Funcionamento da Action de Changelog
A Action de Changelog está configurada para rastrear as atualizações enviadas ao repositório. Sempre que há um novo envio de código (push), a Action lê automaticamente as mensagens dos commits e escreve essas informações na tabela da seção "Changelog" deste próprio arquivo `README.md`. A tabela registra de forma automática a data, a descrição da alteração, o hash do commit e o autor.

### Funcionamento da Action de Release
A Action de Release automatiza a disponibilização de novas versões do projeto. Quando ativada, a rotina empacota os arquivos do repositório em um pacote comprimido (como um arquivo `.zip`) e publica essa nova versão oficialmente na seção "Releases" do GitHub, deixando o código pronto para download e uso.

---

## Changelog

<!-- CHANGELOG:START -->
| Data | Atualização | Hash | Autor |
|:---|:---|:---:|:---|
|  **2026&#8209;10&#8209;28** | docs: atualiza README com requisitos do Trabalho 1 | `f7e9621` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `ba49e18` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | Merge branch 'main' of https://github.com/jamesoaress/Actions | `79ee9c2` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | novamente mudando tabela | `057745f` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `1d9130f` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | mudando tabela | `188c256` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `467772b` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | mudando estilizacao do changelog | `047e661` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `6a433d9` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | feat: adiciona arquivo de teste para gerar a primeira release | `0f6744e` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `999b1c3` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | ci: adiciona workflow para publicar releases automaticamente | `6fd28ed` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `3ff4552` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | outro teste dnvv | `386d533` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `a6935fa` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | Merge branch 'main' of https://github.com/jamesoaress/Actions | `65ef2a9` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | teste: verifica se a automacao do changelog funciona | `fd85b7a` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `3dfa41f` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | Merge branch 'main' of https://github.com/jamesoaress/Actions | `4a70999` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | ci: adiciona workflow de atualização automática do changelog | `0c17a1a` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `cec12c2` |  *github-actions[bot]* |
|  **2026&#8209;10&#8209;15** | Merge branch 'main' of https://github.com/jamesoaress/Actions | `8f9bd0c` |  *jamesoaress* |
|  **2026&#8209;10&#8209;15** | outro teste | `4f10bf3` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `6610ef9` |  *github-actions[bot]* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `af49e29` |  *github-actions[bot]* |
|  **2026&#8209;10&#8209;15** | testando | `bcdb26b` |  *jamesoaress* |
|  **2026&#8209;10&#8209;16** | docs: atualizar changelog no README | `d4be487` |  *github-actions[bot]* |
|  **2026&#8209;10&#8209;15** | docs: configurar changelog automatico | `f2c7629` |  *Copilot* |
|  **2026&#8209;10&#8209;15** | Alterando nome do workflow | `8162715` |  *James Soares* |
|  **2026&#8209;10&#8209;15** | Adiocionando Action | `4efcf6c` |  *James Soares* |
|  **2026&#8209;10&#8209;15** | Initial commit | `363b17c` |  *James Soares* |
<!-- CHANGELOG:END -->
