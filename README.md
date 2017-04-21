# Ether-Minder
Co-author [Valentin Nemcev](https://github.com/valentin-nemcev)
## About Ethereum
Ethereum is an open-source, public, blockchain-based distributed computing platform. It allows to not only use cryptocurrency but also write applications to blockchain (it is called Smart Contracts), which can be executed.

## What does Ether-Minder do?
The contract implements a simpliﬁed idea of beeminder.com (motivation service, which charges a fee in case if he/she do not accomplish his/her challenge).

Page of contract in public test network:

![adding challenge to Ether-Minder](https://pp.userapi.com/c639126/v639126518/1950/PvAHHRvyCd8.jpg)

Ether-Minder has following features:
* Add challenge. A person gives a description of the challenge then sends to contract as much money as much he wants to bet. Also, he should specify the person who will be responsible for marking challenge as completed or failed.
* Mark challenge as completed. In this case, the bet is sent back to the person.
* Mark challenge as failed. In this case, the bet is literally destroyed (money is sent to 0 address)

Adding challenge to Ether-Minder:

![adding challenge to Ether-Minder](https://pp.userapi.com/c639126/v639126518/1947/1xCo8LiK7Rw.jpg)

## Code of contract
Code of contract with comments in English can be found [here](https://github.com/kornilova-l/Ether-Minder/blob/master/code-of-contract).

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
