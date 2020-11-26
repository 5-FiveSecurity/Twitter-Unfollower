
# Twitter Unfollower

Esse é um script em ruby 2.6.5.

# O que o friends.rb faz

Pega todas as contas que você segue;

Salva em um txt algumas informações das contas que você segue;

Cada sleep é de 15 minutos a cada 80 requisições (ele faz 2 ou 3 requisições para o twitter enquanto esse código roda);

O código gera alguns arquivos em .txt para validação das contas que você mexeu. Todos os arquivos ficarão na raiz do projeto. PS: Caso você tenha que rodar mais de uma vez o código, lembre-se de deletar os arquivos antes.

Todos os logs de execução estarão no arquivo `logs.txt.`

# O que o unfollow.rb faz

Depois de rodar o `friends.rb,` você salvou todos os seus friends no arquivo `all_friends_ids.txt;`

Você vai ter salvo todos os seus friends nesse txt, então nesse método você vai escolher em quem vai dar unfollow;

Se você colocar 1, ele será colocado na lista de unfollow, se colocar 2 não será colocado em lista alguma e se escolher 3, será colocado na lista de não decididos;

Após fazer todas as escolhas, o método unfollow_friends irá rodar automaticamente pegando todos os friends que você colocou na lista de unfollow e dando unfollow em cada um;

Uma nova lista de log será gerada no arquivo unfollow_friends.txt.

Todos os logs de execução estarão no arquivo logs.txt.

# O que o lists_destroy_all.rb faz

Ele exclui todas as listas que você é o dono.

Todos os logs de execução estarão no arquivo 
`logs.txt.`
