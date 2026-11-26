# 🐾 PeTinder

Protótipo de aplicação em **Flutter** para exploração de perfis de pets, correspondências (*matches*), adoção, serviços e agendamentos.

---

## ✨ Funcionalidades

* **Descoberta (`lib/screens/discover.dart`):** Navegação e visualização de perfis de animais.
* **Matches (`lib/screens/matches.dart`):** Consulta das correspondências realizadas.
* **Adoção (`lib/screens/adoption.dart`):** Fluxo voltado para adoção de pets.
* **Serviços (`lib/screens/services.dart`):** Catálogo de serviços disponíveis.
* **Agendamentos (`lib/screens/bookings.dart`):** Gestão de reservas e agendamentos.
* **Perfil (`lib/screens/profile.dart`):** Visualização e gestão do perfil.

---

## 📂 Estrutura do Projeto

```text
lib/
├── main.dart            # Ponto de entrada da aplicação
├── data.dart            # Dados simulados de perfis e pets
├── services_data.dart   # Dados simulados de serviços
├── widgets.dart         # Componentes reutilizáveis
└── screens/
    ├── discover.dart    # Tela de descoberta
    ├── matches.dart     # Tela de matches
    ├── adoption.dart    # Tela de adoção
    ├── services.dart    # Tela de serviços
    ├── bookings.dart    # Tela de agendamentos
    └── profile.dart     # Tela de perfil
assets/
└── images/              # Imagens utilizadas no protótipo


🚀 Como Executar o Projeto
1. Clone este repositório: git clone [https://github.com/Victor12345-cpu/PetTinder.git](https://github.com/Victor12345-cpu/PetTinder.git)
2. Acesse a pasta do projeto no terminal: cd PetTinder
3. Instale as dependências: flutter pub get
4. Execute a aplicação: flutter run
