Um script que gera usuários, cada usuário está em um grupo com seus própriosdiretórios. Os usuários do grupo GRP_ADM tem acesso ao diretório "adm" e o "publico", e não pode acessar os demais diretórios como "ven" ou "sec", e assim respectivamente com os outros grupos e usuários. Cada um tem acesso ao seu diretório junto com o diretório "publico". O diretório "publico" pode ser acessado por todos os usuários independentemente do grupo que ele esteja. Todo código está escrito em shell-linux, e o sistema que utilizei foi o linux-ubuntu.