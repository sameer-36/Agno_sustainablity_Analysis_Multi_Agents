# Agno_sustainablity_Analysis_Multi_Agents
Sustainability Task Force – Multi-Agent AI Dashboard  An interactive Streamlit dashboard powered by Agno multi-agents to research and propose sustainable city solutions. This project was developed as part of the Agno Agents Lab: Mission Sustainability.  🚀 Features  Multi-Agent System – 4 specialized AI agents with distinct roles.
#  Sustainability Task Force – Multi-Agent AI
Dashboard
An interactive **Streamlit dashboard** powered by **Agno multi-agents** to research and propose
sustainable city solutions.
This project was developed as part of the **Agno Agents Lab: Mission Sustainability**.
##  Features
- **Multi-Agent System** – 4 specialized AI agents with distinct roles:
- **News Analyst** → Finds recent sustainability news & green city projects.
- **Data Analyst** → Analyzes environmental datasets (CSV) & auto-generates charts.
- **Policy Reviewer** → Summarizes official government sustainability policies.
- **Innovations Scout** → Identifies cutting-edge urban green technologies.
- **Task Force Mode** – All agents collaborate to produce a single **Sustainability Proposal**.
- **Beautiful Dashboard UI** – Card-based layout with icons, modern styling, and wide-screen
support.
- **Data Upload & Visualization** – Upload environmental CSV files → preview + auto-generated
charts.
- **History Tracking** – View past queries & results in expandable sections.
- **Export Reports** – Download results as Markdown or Text files.
## Demo
- Enter a **research topic** (e.g., “How can our city improve air quality?”).
- Choose an **agent** (or full Task Force).
- Upload CSV (if using Data Analyst).
- Click **Run Analysis** n → Get detailed insights.
## Project Structure
 Sustainability-Taskforce
 sustainability_taskforce.py # Main Streamlit app
 .env # Environment variables (API keys)
requirements.txt # Dependencies
 datasets/ # (Optional) Sample CSV files
##  Installation & Setup
1. **Clone the repository**
```bash
git clone https://github.com/your-username/sustainability-taskforce.git
cd sustainability-taskforce
```
2. **Create a virtual environment & install dependencies**
```bash
pip install -r requirements.txt
```
3. **Set up `.env` file**
```ini
GROQ_API_KEY=your_groq_api_key_here
```
4. **Run the app**
```bash
streamlit run sustainability_taskforce.py
```
##  Example Use Case
- The **News Analyst** finds reports on new urban green initiatives.
- The **Data Analyst** analyzes uploaded air quality datasets, generating statistical summaries and
charts.
- The **Policy Reviewer** summarizes government climate and urban policies.
- The **Innovations Scout** discovers emerging technologies (e.g., vertical farming, smart grids).
- The **Task Force** integrates all findings into a **comprehensive sustainability proposal**.
## Tech Stack
- Streamlit → Interactive UI
- Agno → Multi-agent framework
- Groq → LLM backend
- Pandas → Data analysis
- Matplotlib → Data visualization
## n Future Improvements
- Tabbed interface for smoother navigation
- Integration with live sustainability datasets/APIs
- Export to PDF with charts and proposal summary
n With this dashboard, you can **explore sustainability insights** powered by multiple AI agents,
collaborate ideas, and build actionable city proposals.
