# Spring Boot-based Service Provider using Spring Security SAML extension adapted for PULSE

====================

## Project Description

This project expands upon the sample Spring Boot SAML project made by Vincenzo De Notaris with customizations required for deployment in a PULSE environment.

---------

## References

### Spring Boot

Spring Boot makes it easy to create Spring-powered, production-grade applications and services with absolute minimum fuss. It takes an opinionated view of the Spring platform so that new and existing users can quickly get to the bits they need.

- **Website:** [http://projects.spring.io/spring-boot/](http://projects.spring.io/spring-boot/)

### Spring Security SAML Extension

Spring SAML Extension allows seamless inclusion of SAML 2.0 Service Provider capabilities in Spring applications. All products supporting SAML 2.0 in Identity Provider mode (e.g. ADFS 2.0, Shibboleth, OpenAM/OpenSSO, Ping Federate, Okta) can be used to connect with Spring SAML Extension.

- **Website:** [http://projects.spring.io/spring-security-saml/](http://projects.spring.io/spring-security-saml/)

---------

## Project description

Currently Spring Security SAML module doesn't provide a starter for Spring Boot. Moreover, its configuration is XML-based as of this writing. The aim of this project is to explain how to develop a **Service Provider (SP)** which uses **Spring Boot** (`1.3.0.RELEASE`) and **Spring Security SAML Extension** (`1.0.1.RELEASE`), by defining an annotation-based configuration (**Java Configuration**). **Thymeleaf** is also used as template engine.

**SSOCircle** ([ssocircle.com](http://www.ssocircle.com/en/portfolio/publicidp/)) is used as public Identity Provider for test purpose.

- **Author:** Vincenzo De Notaris ([dev@vdenotaris.com](mailto://dev@vdenotaris.com))
- **Website:** [vdenotaris.com](http://www.vdenotaris.com)
- **Version:**  ` 1.2.1.RELEASE `

Thanks to *Vladimír Schäfer* ([github.com/vschafer](https://github.com/vschafer)) for supporting my work.

### Unit tests

I would like to say thank you to *Alexey Syrtsev* ([github.com/airleks](https://github.com/airleks)) for his contribution on unit tests.

| Metric | Result |
| ------------- | -----:|
| Coverage % | 99% |
| Lines Covered | 196 |
| Total Lines | 199 |

### License

    Copyright 2016 Audacious Inquiry, LLC

	Licensed under the Apache License, Version 2.0 (the "License");
	you may not use this file except in compliance with the License.
	You may obtain a copy of the License at

	    http://www.apache.org/licenses/LICENSE-2.0

	Unless required by applicable law or agreed to in writing, software
	distributed under the License is distributed on an "AS IS" BASIS,
	WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
	See the License for the specific language governing permissions and
	limitations under the License.
