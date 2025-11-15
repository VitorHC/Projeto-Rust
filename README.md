CoreFlow Unified - Scaffold generated automatically

Directories created:
- backend/        : Rust (Actix-web) backend skeleton
- frontend/       : static web UI (index.html, styles.css, app.js)
- db/             : SQLite schema (schema.sql)

How to build backend:
1. Install Rust (https://rustup.rs) and Cargo.
2. cd backend
3. cargo build --release
4. cargo run  # or run the compiled binary in target/release

How to run locally (dev):
- Start backend (cargo run) and open frontend/index.html via a small static server or configure actix to serve static files.

- O projeto foi compilado com sucesso e agora inclui o log de execução.

1.  **Localização do Executável:** O executável do backend está em:
    `coreflow_2.0/coreflow_2.0/backend/target/debug/coreflow_project.exe` (no seu ambiente Windows)

2.  **Instrução de Execução (CRÍTICO):**
    Para que as funções de otimização funcionem, você **DEVE** usar o script de inicialização:
    *   **Mova** o arquivo `iniciar_admin.bat` para a pasta `backend/target/debug/`.
    *   **Execute** o `iniciar_admin.bat` (ele forçará a elevação de privilégios).

3.  **Testando o Login:**
    *   **URL:** `http://127.0.0.1:8080`
    *   **Credenciais:** `admin` / `coreflow2024`

4.  **Testando o Log:**
    *   Após executar qualquer ação, clique no novo botão **"Baixar Log de Execução"** para obter o arquivo `coreflow_execution_log.txt` com o histórico completo.
