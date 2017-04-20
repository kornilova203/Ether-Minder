# Ether-Minder
## About Ethereum
Ethereum is an open-source, public, blockchain-based distributed computing platform. It allowes to not only use cryptocurrency but also write applications to blockchain (it is called Smart Contracts), which can be executed.

## What does Ether-Minder do?
The contract implements a simpliﬁed idea of beeminder.com (motivation service, which charges a fee in case if he/she do not accomplish his/her challenge).
Ether-Minder has following features:
* Add challenge. Person gives description of challenge, sends to contract as much money as much he wants to bet. Also he should specify person who will be responsible for marking challenge as complited or failed.
* Mark challenge as complited. In this case bet is sended back to person.
* Mark challenge as failed. In this case bet is literaly destroied (money is sended to 0 address)

## О эфириуме
Ethereum - это платформа для создания децентрализованных онлайн-сервисов на базе блокчейна. Она позволяет не только проводить операции с криптовалютой, но и записывать в blockchain приложения (умные контракты), которые затем можно выполнить.

## Описание контракта Ether-Minder
Контракт реальзует идею сервиса beeminder.com (мотивационный сервис, где, в случае невыполнения поставленной цели, с тебя снимаются деньги) в упрощенном виде на базе Ethereum.
Контракт позволяет:
* Добавить challenge (цель). При этом пользователь указывает описание задачи, переводить на контракт такое количество ether, которое он хочет поставить, и указывает пользователя, который проверит выполнение задачи.
* Отметить challenge выполненным. При этом деньги возвращаются назад
* Отметить challenge проваленным. При этом деньги уничтожаются

## Адрес и интрефейс контракта в публичной тестовой сети ethereum
[Находится здесь](https://github.com/kornilova-l/Ether-Minder/blob/master/address-and-interface.md)
