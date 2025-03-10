# Coleta e Armazenamento dos Dados
A coleta de dados para este projeto foi realizada a partir da plataforma Kaggle, onde um conjunto de dados foi baixado no formato CSV. Inicialmente, para facilitar o acesso e manipulação, os dados serão armazenados no Google Drive e utilizados no ambiente Google Colab, que permite a leitura e o processamento de forma ágil e integrada.

Entretanto, como parte da estratégia de escalabilidade e governança, os dados serão posteriormente migrados para o Google Cloud Platform (GCP), garantindo maior segurança, controle de acesso e integração com ferramentas avançadas de análise.

### Planejamento de Governança dos Dados
Para garantir uma boa governança de dados, será adotada uma estrutura de gerenciamento que define requisitos, procedimentos e responsabilidades ao longo de todo o ciclo de vida dos dados. Para um armazenamento e acesso seguro, teremos a seguinte estratégia:

* Os dados serão armazenados no Cloud Storage da GCP, organizados em um bucket com regras de controle de acesso baseadas em permissões específicas para cada nível de usuário;
* O acesso será restrito por meio de Identity and Access Management (IAM), garantindo que apenas usuários autorizados possam manipular os dados.
