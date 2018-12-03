# RockPaperScissors
etherium, RockPaperScissors

# Смарт-контракт (тестнет Rinkeby):
https://rinkeby.etherscan.io/address/0xf35b4e6cdd4007307944cf40a8579ebb61a889b8#readContract

UPD: В rinkeby очень долгие транзакции, выложил в ropsten:
https://ropsten.etherscan.io/address/0x0fcfd407b1856caa19e4de9c809aff30c1766449

# Как играть?
Перейти на вкладку WriteContract (https://rinkeby.etherscan.io/address/0xf35b4e6cdd4007307944cf40a8579ebb61a889b8#writeContract)
UPD: https://ropsten.etherscan.io/address/0x0fcfd407b1856caa19e4de9c809aff30c1766449#writeContract

Игрок 1:<br/>
1.Зарегистрируйте сумму ставки в поле register, указывайте большой размера газа<br/>
2.Укажите свой выбор в поле choice  из следующих трех: rock, paper, scissors<br/>
  
Игрок 2:<br/>
1.Зарегистрируйте сумму ставки в поле register, указывайте большой размера газа<br/> 
2.Укажите свой выбор в поле choice из следующих трех: rock, paper, scissors<br/>
  
Enjoy!

# Текущие проблемы:
Игрок видит выбор другого игрока в любой момент времени в блокчейне.
Варианты решения: Вместе со ставкой принимать секретное слово, которым впоследствии шифровать выбор игрока: нечто вроде keccak256(seed+choice). Когда выбор обоих игроков сделан, повторно отправить секретные слова для определения победителя.

# Общее впечатление:
Имел дело с Ethereum довольно давно, в последнее время работал исключительно с EOS.io
Надеялся получить задание для этой платформы.
Проблемой для тестирования оказалось то, что в Ethereum тестнете Rinkeby очень медленно подтверждаются транзакции, приходится выставлять большие суммы газа.







  
