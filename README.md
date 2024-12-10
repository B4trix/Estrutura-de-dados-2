🌐 SmartDelivery - Sistema Inteligente de Gestão Logística

SmartDelivery é uma plataforma desenvolvida para revolucionar a logística de entrega, combinando tecnologia avançada e algoritmos otimizados para atender às demandas de transporte com eficiência e precisão.

💡 Propósito do Projeto

	•	Redução de Custos: Planejamento estratégico para minimizar gastos com transporte e tempo de viagem.
	•	Otimização de Recursos: Gestão eficiente da frota com alocação baseada em capacidade e prioridades.
	•	Cumprimento de Prazos: Garantir que todas as entregas sejam realizadas dentro dos horários estabelecidos.
	•	Centralização Inteligente: Seleção automática do ponto de distribuição mais adequado para cada pedido.

⚙️ Funcionalidades do Sistema

	•	Planejamento de Rotas: Utilização de algoritmos para identificar trajetos otimizados.
	•	Geolocalização Integrada: Cálculos precisos de rotas e distâncias com APIs de mapas.
	•	Gerenciamento Operacional: Controle total sobre veículos, centros de distribuição, clientes e entregas.
	•	Interface Responsiva: Navegação simples e intuitiva por meio de menus interativos.

---

🔧 Configuração e Execução

Pré-requisitos

	•	Python 3.9 ou superior
	•	Chave da API para geocodificação (ex.: OpenCage ou Google Maps)
	•	Banco de dados configurado (SQLite ou outro compatível)
```

2 - **Instale as dependências:**
```bash
pip install -r requirements.txt
```

3 - **Configure as variáveis de ambiente:**
-**Crie um arquivo .env na raiz do projeto com as seguintes informações:**
```bash
OPENCAGE_API_KEY=your_api_key_here
NOMINATIM_USER_AGENT=your_user_agent_here
```

4 - **Inicialize o banco de dados:**
```bash
python -m database.init_db
```

## Execução
-**Para iniciar o sistema, execute o menu principal:**
```bash
python visual/menu_principal.py
```

## 📊 Demonstração
<div style="display: flex; justify-content: space-around;">
  <div>
    <strong>Menu Principal</strong><br>
    <img src="image/principal.png" alt="Menu Principal" width="400"/>
  </div>
  <div>
    <strong>Menu Caminhões</strong><br>
    <img src="image/caminhoes.png" alt="Menu Caminhões" width="400"/>
  </div>
  <div>
    <strong>Menu Clientes</strong><br>
    <img src="image/clientes.png" alt="Menu Clientes" width="400"/>
  </div>
</div>
<br>
<div style="display: flex; justify-content: space-around;">
  <div>
    <strong>Menu Entregas</strong><br>
    <img src="image/entregas.png" alt="Menu Entregas" width="400"/>
  </div>
  <div>
    <strong>Menu Centros</strong><br>
    <img src="image/centros.png" alt="Menu Centros" width="400"/>
  </div>
</div>

📊 Visão do Sistema

Interface do Usuário

	•	Gerenciamento de Frota: Adicione, edite e monitore os veículos disponíveis.
	•	Controle de Entregas: Organize as entregas com base em prioridades e localizações.
	•	Centros de Distribuição: Configure os hubs logísticos para otimizar as operações.

🤝 Como Contribuir

	•	Envie sugestões e relatórios de bugs na aba de Issues.
	•	Faça pull requests com melhorias ou novas funcionalidades.

📬 Contato

	•	Autor: [Beatriz Rodrigues]
	•	E-mail: Btrz.rrs@gmail.com




