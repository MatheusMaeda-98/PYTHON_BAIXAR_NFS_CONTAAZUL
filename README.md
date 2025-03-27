# PYTHON_BAIXAR_NFS_CONTAAZUL
BOT desenvolvido para baixar as nfs de vendas no Conta Azul delimitado a um determinado periodo de emissão na plataforma ContaAzul.

É um BOT simples e primitivo, com muito espaço para otimização.
para usar deve-se alterar parte do código.

**Como usar**
- Esse bot está programado apenas para usar na plataforma do ContaAzul, necessário ja ter a conta cadastrado lá.
- Na parte dos "prefs" altere a pasta de caminho do download das nfs para sua preferência
- Na parte do código: email_input.send_keys preencha seu email de acesso dentro das aspas.
- Na parte do código: password_input.send_key preencha sua senha de acesso dentro das aspas.
- Na parte do código: data = "01042023" mude para a data do periodo inicial do intervalo sem as barras (ddmmaaa)
- Na parte do código: data2 mude para a data do periodo final do intervalo sem as barras (ddmmaaa)
- Na parte do código:PESQU = "PSIK" mude para "" caso queira baixar todas as nfs do periodo ou preencha com o nome do cliente que deseja delimitar as nfs a serem baixadas

**Atenção**
Os devs do site com o tempo mudam os caminhos do xpath, então com o tempo é necessário mudar manualmente eles para que o bot funcione.
