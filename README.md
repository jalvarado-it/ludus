# Ludus Templates

Just playing with templates for Ludus - an open-source, API-driven infrastructure management system for building cyber environments.

## 📝 Description

This repository contains custom templates and configurations for [Ludus](https://ludus.cloud/), a system designed to build easy-to-use cyber environments or "ranges" for testing, development, and educational purposes. These templates help automate the deployment and configuration of complex network infrastructures with simple commands.

## 🎯 Purpose

This is an experimental repository where I explore and develop:
- Custom Ludus templates
- Infrastructure configurations
- Network topologies for cyber ranges
- Testing scenarios and environments

## 🏗️ Templates Structure

```
ludus/
├── templates/          # Custom Ludus templates
├── configs/           # Configuration files
├── docs/              # Documentation and guides
├── ranges/           # Range files
└── examples/          # Example implementations
```

## 🚀 Getting Started

### Prerequisites

- [Ludus](https://ludus.cloud/) installed and configured
- Access to a virtualization environment
- Basic understanding of YAML/JSON configuration files

### Installation

1. Clone this repository:
```bash
git clone https://github.com/jalvarado-it/ludus.git
cd ludus
```

2. Review and customize the templates according to your needs

3. Deploy using Ludus:
```bash
ludus range deploy
```

## 📋 Available Templates

| Template | Description | Status |
|----------|-------------|--------|
| `basic-lab` | Simple lab environment | 🚧 In Progress |
| `security-range` | Cybersecurity testing range | 🚧 In Progress |
| `development-env` | Development environment setup | 🚧 In Progress |

> **Note**: This is an experimental repository. Templates are subject to frequent changes and may not be production-ready.

## 🔧 Usage

1. Choose a template from the available options
2. Customize the configuration files as needed
3. Validate your configuration:
```bash
ludus range config get
```
4. Deploy the environment:
```bash
ludus range deploy
```

## 📖 Documentation

- [Ludus Official Documentation](https://docs.ludus.cloud/)
- [Template Development Guide](./docs/template-development.md)
- [Configuration Reference](./docs/configuration.md)

## 🤝 Contributing

This is a personal learning repository, but contributions and suggestions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-template`)
3. Commit your changes (`git commit -m 'Add amazing template'`)
4. Push to the branch (`git push origin feature/amazing-template`)
5. Open a Pull Request

## ⚠️ Disclaimer

This repository is for educational and testing purposes. The templates and configurations provided here are experimental and should be thoroughly tested before use in any production environment.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Related Projects

- [Ludus Core](https://github.com/badsectorlabs/ludus) - Main Ludus project
- [Ludus Templates](https://github.com/Croko-fr/ludus-templates) - French Ludus templates
- [CISA Ludus](https://github.com/cisagov/Ludus) - CISA's Ludus implementation

## 📧 Contact

Created by [@jalvarado-it](https://github.com/jalvarado-it)

---

*Happy templating! 🎮*