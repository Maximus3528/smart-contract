# Разработка смарт контрактов и токенов

## Развертывание Smart Contract
- Как создать токен в Polygon (MATIC) сети [YouTube](https://youtu.be/_Pi1rQEGNKI)
- Как создать токен в BNB Smart Chain (BNB) сети [YouTube](https://youtu.be/sTrGhsmOCZ0)
- Как создать токен в Avalanche C-Chain (AVAX) сети [YouTube](https://youtu.be/O6E7_yK5MWU)
- Как создать токен в Fantom (FTM) сети [YouTube](https://youtu.be/XmR-0mEchEk)

## Blockchain Explorer
- Как опубликовать свой Токен или SmartContract в Blockchain Explorer [YouTube](https://youtu.be/dAnI76aaH3E)
- Как читать смарт контракты [YouTube](https://youtu.be/iXdO5rqXa18)

## Liquidity Tokens
- Как добавить первую ликвидность токена в Uniswap v3 [YouTube](https://youtu.be/YqFfr_iCMBY)
- Как добавить первую ликвидность токена в SushiSwap v3 [YouTube](https://youtu.be/DSr3F65i2bE)
- Как добавить первую ликвидность токена в PancakeSwap v2 [YouTube](https://youtu.be/l0KniFJ2B3g)

## Dex инструменты
- Мое Dex приложение на GitHub  [VladimirGav dApp Tools](https://vladimirgav.github.io/)
- Dex инструменты для анализа и поиска токенов в DexView [YouTube](https://youtu.be/pNisAFWql0U)
- Графики, торги, поиск и анализ токенов в DexTools [YouTube](https://youtu.be/IAxDI-gqTgs)

## Смарт контракты
##### Внимание инвесторам! Важно осознавать, что даже при наличии выгодного контракта всегда существует потенциальный риск вывода ликвидности.
0. [token-simple.sol](token-simple.sol) - Данный пример контракта представляет минимальный набор необходимых функций для работы токена, что придает ему привлекательность для инвесторов. Отсутствие функций, которые могут быть использованы для манипуляций и обмана, делает его особенно надежным. Видео инструкция https://youtu.be/sTrGhsmOCZ0
0. [token-blacklist.sol](token-blacklist.sol) - Пример добавления BlackList в смарт контракт. У владельца добавляется возможность вносить и удалять держателей в BlackList. Для пользователей в Черном Списке блокируется функция transfer. Видео инструкция https://youtu.be/4KNxf1uiShc
0. [token-mint.sol](token-mint.sol) - Пример добавления Mint в смарт контракт. У владельца добавляется возможность создавать новые токены. Видео инструкция https://youtu.be/r_893uh79-Q
0. [token-burn.sol](token-burn.sol) - Пример добавления Burn в смарт контракт. У держателей добавляется возможность сжигать свои токены. Видео инструкция https://youtu.be/eFTky4sZXCw
0. [token-tax-buy.sol](token-tax-buy.sol) - Пример добавления налога на покупку токенов в смарт контракте. У владельца добавляется возможность устанавливать несколько налогов на покупку. Видео инструкция https://youtu.be/ErVpuN0z8sM
0. [token-tax-sell.sol](token-tax-sell.sol) - Пример добавления налога на продажу токенов в смарт контракте. У владельца добавляется возможность устанавливать несколько налогов на продажу. Видео инструкция https://youtu.be/nw4hc0ErOX0
0. [token-tax-transfer.sol](token-tax-transfer.sol) - Пример добавления налога на перевод токенов в смарт контракте. У владельца добавляется возможность устанавливать несколько налогов на перевод. Видео инструкция https://youtu.be/UUqxpC2_kQU
0. [token-tax.sol](token-tax.sol) - Пример добавления налога на покупку, продажу, перевод токенов в смарт контракте. У владельца добавляется возможность устанавливать несколько налогов на покупку, продажу, перевод. Добавлена функция вносить адреса для игнорирования налога. Видео инструкция https://youtu.be/hd0c3PfE_KM
0. [token-tax-in-any-token.sol](token-tax-in-any-token.sol) - Пример добавления налога на покупку, продажу, перевод токенов в любом токене. У владельца добавляется возможность устанавливать несколько налогов на покупку, продажу, перевод в любом токене или ETH путем выполняея обмена токена проекта на нужный токен. Этот пример смарт контракта является дополнением к [token-tax.sol](token-tax.sol). Видео инструкция скоро
0. [token-wallet-limit.sol](token-wallet-limit.sol) - Пример добавления лимита кошелька, в %, на покупку токенов. У владельца добавляется возможность устанавливать максимальный процент владения токенов для одного кошелька. Видео инструкция https://youtu.be/i9_lKv9S0mU
0. [token-wallet-limit-in-tokens.sol](token-wallet-limit-in-tokens.sol) - Пример добавления лимита кошелька, в Токенах, на покупку и получение токенов. У владельца добавляется возможность устанавливать максимальное количество владения токенов для одного кошелька. Видео инструкция скоро
0. [token-transfer-eth.sol](token-transfer-eth.sol) - Пример добавления возможности смарт контракт отправлять ETH (криптовалюта сети). У владельца добавляется возможность отправлять ETH(криптовалюту сети) сети с баланса смарт контракта на любой адрес. Видео инструкция https://youtu.be/utgZLifkCRk
0. [token-transfer-eth-tokens.sol](token-transfer-eth-tokens.sol) - Пример добавления возможности смарт контракт отправлять ETH (криптовалюта сети) и другие Токены. У владельца добавляется возможность отправлять ETH(криптовалюту сети) и другие Токены с баланса смарт контракта на любой адрес. Видео инструкция https://youtu.be/SUjxQ4UElkE
0. [token-transfer-pause.sol](token-transfer-pause.sol) - Пример добавления возможности останавливать торги и все переводы для Токенов проекта. У владельца добавляется возможность ставить на паузу функцию _transfer. Видео инструкция https://youtu.be/VagU94NB2FA
0. [token-multi-owners.sol](token-multi-owners.sol) - Пример добавления нескольких владельцев для смарт контракта. У владельцев добавляется возможность добавлять новых владельцев, удалять текущих, создавать функции которые требуют подтверждения всех владельцев для их выполнения. Видео инструкция https://youtu.be/_GSYMdRi6Zc
0. [wallet-multi-owners.sol](wallet-multi-owners.sol) - Пример создания кошелька с несколькими владельцами на смарт контракте. Смарт контракт может принимать криптовалюту сети (ETH, BNB, MATIC ...) и любые токены в этой сети. Для вывода средств из смарт контракта, требуется подтверждение транзакции всех владельцев. Видео инструкция https://youtu.be/4kByskvGze4
0. [token-whitelist.sol](token-whitelist.sol) - Пример добавления WhiteList в смарт контракт. У владельца добавляется возможность вносить и удалять адреса в WhiteList, а также отключать функцию transfer для всех, кого нет в белом списке. Видео инструкция https://youtu.be/nM5p0UIWMZc
0. [token-stable.sol](token-stable.sol) - Пример стабильного токена со 100% обеспечением. Смарт контракт позволяет создать стабильный токен относительно любого другого токена (ETH, BTC, USDT, USDC ...). После развертывания смарт контракта, владелец стабильного токена может сам указать относительного какого токена он будет стабильным и указать его цену в токене гаранте. Любой желающий может купить или продать любое количество стабильного токена по стабильной цене относительно токена гаранта. Видео инструкция https://youtu.be/TLYF115fWcw
0. [token-anti-bot.sol](token-anti-bot.sol) - Пример внедрения AntiBot. Смарт контракт позволяет используя функцию setStatusAntiBot(true, 1000000000000000000) активировать  активировать AntiBot, который запретит использовать несколько транзакций в одном блоке и установит лимит на перевод. AntiBot активируется на 5 минут, в течение этого времени нужно успеть внести первую ликвидность, если не успели можно активировать повторно. Видео инструкция СКОРО
0. [tokens-multi-transfers.sol](tokens-multi-transfers.sol) - Пример добавления TokensMultiTransfers в смарт контракт. У любого желающего появляется возможность рассылать любые Токены и криптовалюту сети (ETH, BNB, MATIC ...) на множество кошельков как с единой суммой, так и с разной для каждого адреса. Видео инструкция https://youtu.be/GMvkZ-0PtUo
    - Вы можете воспользоваться уже опубликованными контрактами для рассылок токенов и криптовалюты:
    - [BNB Smart Chain (BSC, BEP20) Testnet](https://testnet.bscscan.com/address/0x0910e72437b6212dda969b6ec82fbcfbb646bf8f#writeContract)
    - [BNB Smart Chain (BSC, BEP20)](https://bscscan.com/address/0x0910e72437b6212dda969b6ec82fbcfbb646bf8f#writeContract)
    - [Polygon (MATIC)](https://polygonscan.com/address/0x0910e72437b6212dda969b6ec82fbcfbb646bf8f#writeContract)
0. [staking-tokens.sol](staking-tokens.sol) - Пример смарт контракта для стейкинга токенов. У любого владельца смарт контракта токена появляется возможность создать стейкинг этих токенов. После создания стейкинга любой держатель этих токенов, может их положить в стейкинг и получать вознаграждения. Видео инструкция https://www.youtube.com/watch?v=CoB0UzyXsSo
    - Вы можете воспользоваться уже опубликованными смарт контрактами для создания стейкингов:
    - [BNB Smart Chain (BSC, BEP20) Testnet](https://testnet.bscscan.com/address/0x514e1f0ced3fa63d27b6012592564ca74a819378#writeContract)
    - [BNB Smart Chain (BSC, BEP20)](https://bscscan.com/address/0x514e1f0ced3fa63d27b6012592564ca74a819378#writeContract)
    - [Polygon (MATIC)](https://polygonscan.com/address/0x514e1f0ced3fa63d27b6012592564ca74a819378#writeContract)
0. [airdrop-tokens.sol](airdrop-tokens.sol) - Пример смарт контракта для раздачи аирдропов. У любого владельца смарт контракта токена появляется возможность создать раздачу аирдропа. После создания аирдропа, все пользователи которые есть в списке получателей, могут потребовать свои токены до даты завершения. Смарт контракт имеет гибкие настройки, например: Можно раздаваемые токены держать как на этом смарт контракте, так и на кошельке владельца; Можно указать действие после завершения, сжечь оставшиеся токены или вернуть владельцу. Видео инструкция https://youtu.be/icQ6UxUOE5k?si=N1AWifbp7tJv3Zsm
    - Вы можете воспользоваться уже опубликованными смарт контрактами для раздачи аирдропа:
    - [BNB Smart Chain (BSC, BEP20) Testnet](https://testnet.bscscan.com/address/0xee8b3cb26a14c7c74a6786e08df0b4b6582e9d65#writeContract)
    - [BNB Smart Chain (BSC, BEP20)](https://bscscan.com/address/0xee8b3cb26a14c7c74a6786e08df0b4b6582e9d65#writeContract)
    - [Polygon (MATIC)](https://polygonscan.com/address/0xee8b3cb26a14c7c74a6786e08df0b4b6582e9d65#writeContract)
    
# Контакты
- [Telegram](https://t.me/Vladimir_Gav)
- [YouTube](https://www.youtube.com/@vladimirgav)