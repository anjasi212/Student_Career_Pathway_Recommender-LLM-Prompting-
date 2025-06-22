# Student_Career_Pathway_Recommender-LLM-Prompting-

An intelligent career guidance system that uses AI and LangChain to provide personalized career recommendations based on student interests, academic strengths, and performance.

## 🌟 Key Features

- **AI-Powered Recommendations**: Personalized career suggestions with confidence scores
- **6 Career Categories**: STEM, Arts & Creative, Business & Finance, Healthcare, Education, Sports & Fitness
- **Skills Gap Analysis**: Identify required skills and get learning roadmaps
- **Conversational Memory**: Context-aware recommendations across sessions

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/yourusername/career-recommender.git
cd career-recommender
pip install -r requirements.txt
```

### Setup
```bash
# Set OpenAI API key
export OPENAI_API_KEY="your_api_key_here"

# Run the application
python career_recommender.py
```

## 💻 Technology Stack

- **Python 3.8+** with LangChain and OpenAI GPT-3.5
- **Key Libraries**: `langchain-openai`, `pydantic`, `dataclasses`
- **Features**: Structured prompts, conversation memory, fallback system

## 🎮 Usage

Choose from 5 main options:
1. **Get AI Recommendations** - Personalized career suggestions
2. **Explore Career Categories** - Browse detailed career information
3. **Skills Gap Analysis** - Identify learning needs for target careers
4. **View Conversation History** - Track your exploration journey
5. **Database Statistics** - View system coverage metrics

## 📊 Coverage

- **12+ Career Paths** across 6 major categories
- **Comprehensive Data**: Salary ranges, skills, education requirements
- **AI-Generated Insights**: Industry trends and growth outlook

## 🔧 Configuration

```python
# Model settings in career_recommender.py
self.llm = ChatOpenAI(
    model="gpt-3.5-turbo",
    temperature=0.7,
    max_tokens=800
)
```

## 🧪 Testing

Run in test mode to evaluate predefined profiles:
```bash
python career_recommender.py
# Select option 2 for automated testing
```

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/new-feature`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature/new-feature`)
5. Open Pull Request

## 📝 License

MIT License - see [LICENSE](LICENSE) file for details.

**THANKS** 🌟
