meu_projeto/
│
├── src/
│   └── meu_dominio/
│       ├── __init__.py
│       │
│       ├── domain/                    # Camada de Domínio (núcleo)
│       │   ├── __init__.py
│       │   ├── entities/              # Entidades
│       │   │   ├── __init__.py
│       │   │   └── usuario.py
│       │   ├── value_objects/         # Objetos de Valor
│       │   │   ├── __init__.py
│       │   │   └── email.py
│       │   ├── aggregates/            # Agregados
│       │   │   ├── __init__.py
│       │   │   └── pedido.py
│       │   ├── repositories/          # Interfaces de Repositórios
│       │   │   ├── __init__.py
│       │   │   └── usuario_repository.py
│       │   ├── services/              # Serviços de Domínio
│       │   │   ├── __init__.py
│       │   │   └── calculadora_preco.py
│       │   └── events/                # Eventos de Domínio
│       │       ├── __init__.py
│       │       └── usuario_criado.py
│       │
│       ├── application/               # Camada de Aplicação
│       │   ├── __init__.py
│       │   ├── use_cases/             # Casos de Uso
│       │   │   ├── __init__.py
│       │   │   └── criar_usuario.py
│       │   └── dtos/                  # Data Transfer Objects
│       │       ├── __init__.py
│       │       └── usuario_dto.py
│       │
│       ├── infrastructure/            # Camada de Infraestrutura
│       │   ├── __init__.py
│       │   ├── persistence/           # Implementações de Repositórios
│       │   │   ├── __init__.py
│       │   │   └── usuario_repository_impl.py
│       │   ├── database/              # Configuração de BD
│       │   │   ├── __init__.py
│       │   │   └── connection.py
│       │   └── messaging/             # Mensageria
│       │       └── __init__.py
│       │
│       └── presentation/              # Camada de Apresentação
│           ├── __init__.py
│           ├── api/                   # Controllers/APIs
│           │   ├── __init__.py
│           │   └── usuario_controller.py
│           └── cli/                   # Interface CLI
│               └── __init__.py
│
└── tests/                             # Testes espelhando a estrutura
    ├── domain/
    ├── application/
    └── infrastructure/