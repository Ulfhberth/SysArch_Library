# SysArch_Library

**Open Repository for Libraries, Packages, and Profiles for Efficient System Architecture Modeling with Eclipse Papyrus**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Eclipse Papyrus](https://img.shields.io/badge/Eclipse-Papyrus-orange.svg)](https://eclipse.dev/papyrus/)
[![SysML 1.6](https://img.shields.io/badge/SysML-1.6-green.svg)](https://www.omg.org/spec/SysML/1.6/)

## 📋 About This Repository

This repository provides a comprehensive collection of reusable components for system modeling with Eclipse Papyrus. It has been developed to increase efficiency when modeling complex system architectures and to promote best practices for collaborative work.

### Goals

- **Reusability**: Providing standardized libraries and profiles for common modeling tasks
- **Extensibility**: Flexible foundation for project- and domain-specific customizations
- **Collaboration**: Fostering exchange and cooperation within the system modeling community
- **Best Practices**: Demonstrating proven approaches for system architecture modeling

## 📁 Repository Structure

```
SysArch_Library/
├── 01_SystemModeling_StandardLibraries/
│   └── Standard libraries for system modeling
├── 02_SystemModeling_Profiles/
│   └── UML/SysML profiles and extensions
├── 03_SystemModeling_ProjectsAnd Examples/
│   └── Example projects and use cases
└── .metadata/
    └── Eclipse workspace metadata
```

### Directory Description

#### 01_SystemModeling_StandardLibraries
Contains reusable model libraries with predefined elements, stereotypes, and structures for typical system modeling scenarios.

#### 02_SystemModeling_Profiles
Collection of UML/SysML profiles for customizing and extending the modeling language for specific domains and use cases.

#### 03_SystemModeling_ProjectsAnd Examples
Example projects and reference models demonstrating the use of libraries and profiles.

## 🚀 Getting Started

### Prerequisites

- **Eclipse Papyrus** (Desktop or Classic version)
- **SysML 1.6 Plugin** for Eclipse Papyrus
- Java Runtime Environment (JRE) 11 or higher

### Installing Eclipse Papyrus

1. **Download Papyrus**
   - Visit the [Eclipse Papyrus Download Page](https://eclipse.dev/papyrus/downloads/index.html)
   - Choose **Papyrus-Desktop** (recommended) or **Papyrus-Classic**
   - Download the version appropriate for your operating system

2. **Install SysML 1.6**
   
   **Option A: Via Eclipse Marketplace (recommended)**
   - Open Papyrus
   - Navigate to `Help` → `Eclipse Marketplace`
   - Search for "Papyrus SysML 1.6"
   - Click `Install` and follow the instructions
   - Details: [Eclipse Marketplace - Papyrus SysML 1.6](https://marketplace.eclipse.org/content/papyrus-sysml-16)

   **Option B: Via Update Site**
   - Open Papyrus
   - Navigate to `Help` → `Install New Software...`
   - Click `Add...` and add the following update site:
     ```
     https://download.eclipse.org/modeling/mdt/papyrus/papyrus-desktop/components/sysml16/releases/2.4.0/p2/
     ```
   - Select the desired SysML 1.6 features
   - Follow the installation instructions
   - Restart Eclipse after installation

3. **Installation Guide**
   - Detailed steps can be found here: [How to install Papyrus SysML 1.6](https://marketplace.eclipse.org/content/papyrus-sysml-16/help)

### Clone the Repository

```bash
git clone https://github.com/Ulfhberth/SysArch_Library.git
```

### Using in Eclipse Papyrus

1. **Set Up Workspace**
   - Open Eclipse Papyrus
   - Select `File` → `Import` → `General` → `Existing Projects into Workspace`
   - Navigate to the cloned repository directory
   - Select and import the desired projects

2. **Use Libraries and Profiles**
   - Open your modeling project
   - Import the required libraries from `01_SystemModeling_StandardLibraries`
   - Apply profiles from `02_SystemModeling_Profiles` to your models
   - Use the examples from `03_SystemModeling_ProjectsAnd Examples` as reference

## 📚 Usage

### Importing Libraries

1. Open your Papyrus model
2. Right-click on the root package
3. `Import` → `Import Registered Package` or `Import Library`
4. Select the desired library from the repository

### Applying Profiles

1. Open your model in Papyrus
2. Right-click on the package you want to apply the profile to
3. `UML Editor` → `Apply Profile`
4. Select the desired profile from `02_SystemModeling_Profiles`

## 🤝 Contributing

Contributions to expand and improve this repository are warmly welcomed!

### How to Contribute

1. **Fork** this repository
2. Create a **Feature Branch** (`git checkout -b feature/NewLibrary`)
3. **Commit** your changes (`git commit -m 'Add new library for XYZ'`)
4. **Push** to the branch (`git push origin feature/NewLibrary`)
5. Open a **Pull Request**

### Guidelines

- Ensure your models are compatible with Eclipse Papyrus and SysML 1.6
- Document new libraries and profiles adequately
- Add examples demonstrating the use of new components
- Follow the existing folder structure

## 📖 Documentation

Further information about Eclipse Papyrus and SysML:

- [Eclipse Papyrus Documentation](https://eclipse.dev/papyrus/documentation/)
- [SysML 1.6 Specification (OMG)](https://www.omg.org/spec/SysML/1.6/)
- [Papyrus User Guide](https://wiki.eclipse.org/Papyrus_User_Guide)
- [SysML Tutorial](https://sysml.org/.res/docs/tutorial/SysML-Tutorial.pdf)

## 📄 License

This project is licensed under the **GNU General Public License v3.0**. See [LICENSE](LICENSE) for more details.

## 👥 Authors

- **Ulfhberth** - *Initial work* - [GitHub Profile](https://github.com/Ulfhberth)

## 🌟 Acknowledgments

- Eclipse Papyrus Community
- SysML Working Group
- All contributors to this repository

## 📞 Contact & Support

- **Issues**: Please use the [Issue Tracker](https://github.com/Ulfhberth/SysArch_Library/issues) for bug reports and feature requests
- **Discussions**: For general questions and discussions, you can use [Discussions](https://github.com/Ulfhberth/SysArch_Library/discussions)

---

**Note**: This repository is under active development. Changes and extensions are made regularly.
