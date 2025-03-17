# MaxGuruAI 🔍

<div align="center">
  <h3>AI-Driven On-Chain Data Analyst | AI 驱动的链上数据分析师</h3>
  <p>Focus on real-time insights and analysis of cryptocurrency markets</p>
  <p>专注于加密货币市场的实时洞察和分析</p>
</div>

## 📊 Overview | 概述

[EN] MaxGuruAI is a professional cryptocurrency market analysis AI agent that combines blockchain data analysis, market insights, and social media interaction capabilities. It can track fund flows, identify market anomalies, predict trends, and expose potential fraudulent projects.

[中文] MaxGuruAI 是一个专业的加密货币市场分析 AI 代理，结合了区块链数据分析、市场洞察和社交媒体互动功能。它能够追踪资金流向、识别市场异常、预测趋势，并揭露潜在的欺诈项目。

## 🌟 Core Features | 核心特性

### 🔍 Professional Analysis Capabilities | 专业分析能力
- On-chain data tracking and analysis | 链上数据追踪和分析
- Market trend prediction | 市场趋势预测
- Fraud project identification | 欺诈项目识别
- Fund flow tracking | 资金流向追踪
- Sonic ecosystem expert | Sonic 生态系统专家

### 💡 Unique Advantages | 独特优势
- Bilingual interaction (Chinese & English) | 双语交互（中英文）
- First principles-based analysis | 基于第一性原理的分析
- Sharp and direct viewpoints | 犀利直接的观点表达
- Deep market insights | 深度的市场洞察
- Multidimensional knowledge background | 多维度知识背景
  - Philosophy | 哲学
  - Psychology | 心理学
  - Finance | 金融学

### 🤖 Technical Integration | 技术集成
- DeepSeek AI model support | DeepSeek AI 模型支持
- Multi-platform social media access | 多平台社交媒体接入
- Real-time data analysis | 实时数据分析
- Plugin architecture | 插件化架构

## 🛠️ Tech Stack | 技术栈

### Core Components | 核心组件
- Model Provider | 模型提供商: DeepSeek
- Client Support | 客户端支持: Twitter, Telegram, Lens
- Data Sources | 数据源: CoinGecko, GoPlus, Web3 Data

### Plugin System | 插件系统
```typescript
plugins: [
    "@elizaos/plugin-web-search",    // 网页搜索
    "@elizaos/plugin-coingecko",     // 加密货币数据
    "@elizaos/plugin-evm",           // EVM链分析
    "@elizaos/plugin-trustdb",       // 信任数据库
    "@elizaos/plugin-goplus",        // 安全分析
    "@elizaos/plugin-twitter"        // 推特集成
]
```

## 🚀 Quick Start | 快速开始

### Installation | 安装
```bash
# Clone the project | 克隆项目
git clone [repository-url]

# Install dependencies | 安装依赖
pnpm install

# Configure environment variables | 配置环境变量
cp .env.example .env
```

### Configuration | 配置
Configure necessary API keys in the .env file | 在 .env 文件中配置必要的 API 密钥：
```env
DEEPSEEK_API_KEY=your-api-key
TWITTER_USERNAME=MaxGuruAI
TELEGRAM_BOT_TOKEN=your-bot-token
COINGECKO_API_KEY=your-api-key
```

### Run | 运行
```bash
pnpm build
pnpm start
```

## 💻 Usage Examples | 使用示例

### Market Analysis | 市场分析
```typescript
const maxGuru = new MaxGuruAI();
const analysis = await maxGuru.generateResponse("分析 BTC 最近的价格走势");
```

### Social Media Posting | 社交媒体发布
```typescript
const post = await maxGuru.generatePost("加密货币市场分析");
```

## 🎯 Use Cases | 应用场景

1. Market Analysis | 市场分析
   - Real-time market trend analysis | 实时市场趋势分析
   - Price trend prediction | 价格走势预测
   - Market sentiment assessment | 市场情绪评估

2. Risk Warning | 风险预警
   - Fraud project identification | 欺诈项目识别
   - Abnormal fund flow detection | 资金流向异常检测
   - Market manipulation warning | 市场操纵预警

3. Investment Advice | 投资建议
   - Data-driven investment strategies | 基于数据的投资策略
   - Risk assessment | 风险评估
   - Opportunity identification | 机会识别

## ⚙️ Configuration Options | 配置选项

### Basic Settings | 基础设置
```json
{
    "name": "MaxGuruAI",
    "modelProvider": "deepseek",
    "clients": ["lens", "twitter", "telegram"]
}
```

### Publishing Settings | 发布设置
```json
{
    "POST_INTERVAL_MAX": "480",
    "POST_INTERVAL_MIN": "240",
    "POST_IMMEDIATELY": "true"
}
```

## 🤝 Community Interaction | 社区互动

- Twitter | 推特: [@MaxGuruAI](https://twitter.com/MaxGuruAI)
- Telegram | 电报: [MaxGuruAI Bot](https://t.me/MaxGuruAI_bot)

## 📝 License | 许可证

MIT License | MIT 许可证

## ⚠️ Disclaimer | 免责声明

[EN] The analysis and suggestions provided by MaxGuruAI are for reference only and do not constitute investment advice. Users should bear their own risks when using this tool for investment decisions.

[中文] MaxGuruAI 提供的分析和建议仅供参考，不构成投资建议。用户应自行承担使用本工具进行投资决策的风险。