.# PromptNet

# PromptNet Product Recommender

A .NET console application that leverages OpenAI's GPT-3.5 API to provide intelligent product recommendations based on user-specified categories.

## 🌟 Features

- Category-based product recommendations using GPT-3.5
- Simple console interface for user interaction
- Secure API key management through configuration
- Robust error handling and JSON response parsing
- Clean architecture with separated data access layer

## 📋 Prerequisites

- .NET 6.0 or higher
- OpenAI API key
- Visual Studio 2022 or preferred .NET IDE

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/dwarkeshv/PromptNet.git
```

2. Navigate to the project directory:
```bash
cd PromptNet
```

3. Configure your OpenAI API key:
   - Open `appsettings.json`
   - Replace the placeholder API key with your actual OpenAI API key

4. Build and run the application:
```bash
dotnet build
dotnet run
```

## 💻 Usage

1. Launch the application
2. Enter a product category when prompted 
3. The application will return AI-powered recommendations for products in that category

## 🔧 Configuration

The application uses `appsettings.json` for configuration:

```json
{
  "OpenAI": {
    "ApiKey": "your-api-key-here"
  }
}
```
## ⚠️ Error Handling

The application includes comprehensive error handling for:
- HTTP request failures
- JSON parsing errors
- General exceptions

## 🔒 Security

- API key is stored in configuration file
- Never commit your actual API key to version control
- Use environment variables or secure secrets management in production

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
