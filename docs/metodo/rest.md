# Rest API
---
## Oque é Rest?
Um conjunto de regras chamada de representational state transfer("representação
de transferência de estado"), que é utilizada dês dos anos 2000 para a padronização
de APIS.
---
## Formato
Uma requisição http com formato específico como

![](../images/crud.png)

https://left4dev.com/**POST**/dino

resultado: 
```JSON
Accept: application/json
Authorization: <token>

{
    "face":"🦖"
}
```
### Headers
- Accept é onde fica o formato no qual você quer os dados
- Autorization autentica se você pode ou não acessar os dados
### Body
Contêm os dados da mensagem de resposta, estude sobre HTTP para aprender mais sobre