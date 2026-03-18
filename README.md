@echo off
Title Techsolution - Restaurador de Arquivos

cd Organizações Documentos


md "Documentos" "Imagens" "Dev_Web" "Sistema" "Multimidia" 2>nul

:: 1. Documentos
move *.docx "Documentos"
move *.xlsx "Documentos"
move *.pdf "Documentos"
move *.txt "Documentos"
move *.rtf "Documentos"
move *.csv "Documentos"
move *.doc "Documentos"
move *.log "Documentos"
move *.pptx "Documentos"

:: 2. Imagens
move *.jpg "Imagens"
move *.png "Imagens"
move *.ico "Imagens"
move *.gif "Imagens"
move *.bmp "Imagens"
move *.svg "Imagens"
move *.jpeg "Imagens"
move *.tiff "Imagens"
move *.raw "Imagens"

:: 3. Dev_Web
move *.html "Dev_Web"
move *.css "Dev_Web"
move *.js "Dev_Web"
move *.py "Dev_Web"
move *.sql "Dev_Web"
move *.java "Dev_Web"
move *.json "Dev_Web"
move *.php "Dev_Web"
move *.xml "Dev_Web"
move *.yml "Dev_Web"

:: 4. Sistema
move *.exe "Sistema"
move *.msi "Sistema"
move *.dll "Sistema"
move *.ini "Sistema"
move "comando.bat" "Sistema"
move *.sys "Sistema"
move *.inf "Sistema"
move *.reg "Sistema"
move *.bin "Sistema"
move *.vbs "Sistema"

:: 5. Multimidia
move *.mp3 "Multimidia"
move *.mp4 "Multimidia"
move *.zip "Multimidia"
move *.rar "Multimidia"
move *.wav "Multimidia"
move *.mkv "Multimidia"
move *.7z "Multimidia"
move *.iso "Multimidia"
move *.ogg "Multimidia"
move *.flv "Multimidia"
