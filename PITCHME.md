## OAuth2.0 и OpenID Connect
Современные стандарты авторизации для web и микросервисов

---
## Введение в web auth

---

#### Что это такое - OAuth и OpenID Connect? 

---
#### OAuth 2.0 
Фреймворк для описания делегации авторизации [RFC 6749] 
 
---
#### Web auth - работа через токены - что даёт


---  
#### Profile, token introspection

---
#### Fine grained permissions


---
## OAuth 

---
#### Self-contained token, JWT 
--- 
#### Участники OAuth
- *User* - Пользователь, владелец каких-то ресурсов  
- *Client* - клиентское приложение, которое хочет получить доступ к ресурсу пользователя / к API 
- *Resource Server* - Сервер, на котором размещены ресурсы (API работы с ресурсом)
- *Authorization Server* - Сервер авторизации

---
#### Пример - Google photos
- *User* - Пользователь с аккаунтом на Goolge и фотографиями с Google Photos 
- *Client* - Flickr, который хочет скачать фото с Google-аккаунта пользователя  
- *Resource Server* - Google Photos API  
- *Authorization Server* - Сервер авторизации Google 

---
#### Пример 2 - Банк
- *User* - Клиент Банка  
- *Client* - Приложение домашней бухгалтерии, которому нужно получать остатки на счетах пользователя   
- *Resource Server* - API работы со счетами /accounts  
- *Authorization Server* - Сервер авторизации Банка 

---
#### Типы клиентов 
- *Public* - SPA, Native apps
- *Confidential* - Обычный Web app с backend'ом
  
---
#### Client secret 

---

#### Client secret with user creds

---
#### Direct grant

---
#### Auth code flow 

---

## OpenID Connect

---
#### Чем отличается 
	
---	
#### Hybrid flow

---
## Keycloak

* Сервер авторизации с поддержкой стандартов OAuth и OIDC
* Open-source by Red Hat
* В docker
* на Jboss Wildfly 
* кластризуется 
* ...

--- 
#### Проект и установка

---
#### Тестовый клиент

---

## Расширения

---
#### PKCE
Proof Key for Code Exchange

--- 
	 









## Конец
