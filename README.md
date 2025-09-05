# Inicializar o Git
git init

# Adicionar todos os arquivos
git add .

# Primeiro commit
git commit -m "Primeiro commit do site de casamento"

# Conectar ao repositório GitHub
git remote add origin <URL_DO_SEU_REPOSITORIO>
# Renomear a branch principal (se necessário)
git branch -M main

# Enviar arquivos para o GitHub
git push -u origin main
