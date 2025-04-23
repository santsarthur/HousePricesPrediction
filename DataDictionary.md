### 📚 Dicionário de Dados — Projeto House Prices

Tabela com a descrição das variáveis do dataset utilizado no projeto de machine learning para previsão de preços de casas.

### 🔹 Variáveis Gerais

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| MSSubClass            | Tipo de habitação (ex: 20 = 1 andar, 1946+).                              |
| MSZoning              | Zoneamento (ex: RL = Residencial Baixa Densidade).                        |
| LotFrontage           | Metros de frente do terreno conectados à rua.                             |
| LotArea               | Tamanho do terreno (em pés²).                                             |
| Street                | Tipo de rua (Pave = asfaltada).                                           |
| Alley                 | Tipo de acesso por beco (NA = sem acesso).                                |
| LotShape              | Formato do terreno (Reg = regular).                                       |
| LandContour           | Topografia do terreno (Lvl = plano).                                      |
| Utilities             | Utilidades disponíveis.                                                   |
| LotConfig             | Configuração do lote (Inside, Corner...).                                 |
| LandSlope             | Inclinação (Gtl = suave).                                                 |
| Neighborhood          | Bairro (ex: CollgCr = College Creek).                                     |
| Condition1 / Condition2 | Proximidade com vias/ferrovias.                                         |
 
### 🔹 Construção e Estilo

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| BldgType              | Tipo de construção (1Fam = casa individual).                              |
| HouseStyle            | Estilo da casa (1Story, 2Story...).                                       |
| OverallQual           | Qualidade geral (1 a 10).                                                 |
| OverallCond           | Condição geral (1 a 10).                                                  |
| YearBuilt             | Ano de construção original.                                               |
| YearRemodAdd          | Ano da reforma (se houver).                                               |
| RoofStyle / RoofMatl  | Tipo e material do telhado.                                               |
| Exterior1st / Exterior2nd | Material externo (principal e secundário).                            |
| MasVnrType / MasVnrArea | Tipo e área do revestimento de alvenaria.                               |
| ExterQual / ExterCond | Qualidade e condição externa.                                             |

### 🔹 Fundação e Porão

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| Foundation            | Tipo de fundação.                                                         |
| BsmtQual / BsmtCond / BsmtExposure | Qualidade, condição e exposição do porão.                    |
| BsmtFinType1 / BsmtFinType2 | Tipo de acabamento do porão.                                        |
| BsmtFinSF1 / BsmtFinSF2 / BsmtUnfSF / TotalBsmtSF | Áreas do porão (acabadas e não).              |

### 🔹 Sistemas Internos

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| Heating / HeatingQC   | Tipo e qualidade do aquecimento.                                          |
| CentralAir            | Ar-condicionado central (Y/N).                                            |
| Electrical            | Sistema elétrico.                                                         |

### 🔹 Área Interna

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| 1stFlrSF / 2ndFlrSF    | Áreas do 1º e 2º andar.                                                  |
| LowQualFinSF          | Área de acabamento de baixa qualidade.                                    |
| GrLivArea             | Área habitável acima do solo.                                             |

### 🔹 Banheiros e Quartos

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| BsmtFullBath / BsmtHalfBath | Banheiros no porão.                                                 |
| FullBath / HalfBath   | Banheiros acima do porão.                                                 |
| BedroomAbvGr          | Quartos acima do porão.                                                   |
| KitchenAbvGr / KitchenQual | Cozinhas e qualidade.                                                |
| TotRmsAbvGrd          | Total de cômodos acima do porão.                                          |

### 🔹 Outros Recursos Internos

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| Functional            | Funcionalidade geral da casa.                                             |
| Fireplaces / FireplaceQu | Lareiras e qualidade.                                                  |

### 🔹 Garagem

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| GarageType / GarageYrBlt / GarageFinish / GarageCars / GarageArea / GarageQual / GarageCond | Informações da garagem. |

### 🔹 Área Externa

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| PavedDrive            | Entrada pavimentada (Y/N/P).                                              |
| WoodDeckSF / OpenPorchSF / EnclosedPorch / 3SsnPorch / ScreenPorch | Áreas externas.              |
| PoolArea / PoolQC     | Piscina e qualidade.                                                      |
| Fence                 | Tipo de cerca.                                                            |

### 🔹 Outros

| Variável              | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| MiscFeature / MiscVal | Outros recursos (ex: Shed) e valor.                                       |
| MoSold / YrSold       | Mês e ano da venda.                                                       |
| SaleType / SaleCondition | Tipo e condição da venda.                                              |
