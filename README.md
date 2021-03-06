# Mao Service Framework :)
[![Build Status](https://travis-ci.org/MaoJianwei/Mao_Service_Framework.svg?branch=master)](https://travis-ci.org/MaoJianwei/Mao_Service_Framework)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/MaoJianwei/MaoFramework/blob/master/LICENSE)

A lightweight service framework for you to build up **modular System** or create **simple Applications**.

.

**Bootstrap.java** is the entry of this framework, and it can be an **example** for you to do some **extension** / **develop** your Apps based on this service framework.

## Architecture

***Your Apps/Modules*** ---register-to---> **ModuleManager** ---send-to-run---> **RunningCore**

***Your Web needs*** ---extend---> **WebController** ---loaded-by---> **WebSystem** ---register-to---> **ModuleManager**

(WebSystem / WebController are based on Spring Boot & MVC)

.

## ***Dependency Injection*** is beta version now!

implemented with ***MaoAbstractRunningTask*** and ***@MaoReference*** annotation

.

## Architect

Jianwei Mao

https://www.MaoJianwei.com/

E-mail: maojianwei2012@126.com

.

![JetBrains Logo](https://www.jetbrains.com/favicon-32x32.png) Supported by [JetBrains IDEA Open Source License](https://www.jetbrains.com/?from=Mao_Service_Framework) 2020-2021. 
