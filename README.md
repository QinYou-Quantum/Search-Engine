# Search-Engine
Lightweight Search Engine
A lightweight, learning-oriented search engine prototype for educational purposes.

## 🌐 Multilingual Version / Многоязычная версия / Versión multilingüe / Version multilingue / 多言語バージョン / 多语言版本
- [English](#english)
- [Русский](#русский)
- [Español](#español)
- [Français](#français)
- [日本語](#日本語)
- [中文](#中文)

---

## English
### Project Overview
Search-Engine is a personal learning project focused on building a simplified search engine prototype. This project covers core search engine concepts including web crawling, data indexing, keyword retrieval, and basic result ranking algorithms.

### Features
- Basic web crawler for static page scraping
- Inverted index implementation for fast keyword lookup
- Simple TF-IDF based result ranking
- REST API for search query interaction
- Lightweight and easy-to-extend code structure

### Tech Stack
- Primary Language: Python 3.8+
- Core Libraries: 
  - BeautifulSoup4 (web parsing)
  - Requests (HTTP requests)
  - NLTK (text processing)
  - Flask (API server)
- Database: SQLite (for index storage)

### Quick Start
#### Prerequisites
```bash
pip install -r requirements.txt
Run the Search Engine
bash
运行
# Start crawler to collect data
python src/crawler.py --url https://example.com --depth 2

# Build index
python src/indexer.py

# Start API server
python src/server.py

# Test search
curl http://localhost:5000/search?q=your_keyword
Project Structure
plaintext
Search-Engine/
├── src/
│   ├── crawler.py       # Web crawling module
│   ├── indexer.py       # Index building module
│   ├── ranker.py        # Result ranking module
│   ├── server.py        # API server
│   └── utils.py         # Helper functions
├── data/                # Crawled data and index storage
├── tests/               # Unit tests
├── requirements.txt     # Dependencies
└── README.md            # Project documentation
License
MIT License
Copyright (c) [Year] QinYou-Quantum (Qin Xiaoyou)
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
Русский
Обзор проекта
Search-Engine — это личный учебный проект, направленный на создание упрощенного прототипа поисковой системы. Проект охватывает основные концепции поисковых систем, включая веб-краулинг, индексацию данных, поиск по ключевым словам и базовые алгоритмы ранжирования результатов.
Функции
Базовый веб-краулер для парсинга статических страниц
Реализация инвертированного индекса для быстрого поиска по ключевым словам
Простое ранжирование результатов на основе TF-IDF
REST API для взаимодействия с поисковыми запросами
Легковесная и легко расширяемая структура кода
Технологический стек
Основной язык: Python 3.8+
Основные библиотеки:
BeautifulSoup4 (парсинг веб-страниц)
Requests (HTTP-запросы)
NLTK (обработка текста)
Flask (API-сервер)
База данных: SQLite (для хранения индекса)
Быстрый старт
Предварительные требования
bash
运行
pip install -r requirements.txt
Запуск поисковой системы
bash
运行
# Запуск краулера для сбора данных
python src/crawler.py --url https://example.com --depth 2

# Создание индекса
python src/indexer.py

# Запуск API-сервера
python src/server.py

# Тест поиска
curl http://localhost:5000/search?q=ваше_ключевое_слово
Структура проекта
plaintext
Search-Engine/
├── src/
│   ├── crawler.py       # Модуль веб-краулинга
│   ├── indexer.py       # Модуль создания индекса
│   ├── ranker.py        # Модуль ранжирования результатов
│   ├── server.py        # API-сервер
│   └── utils.py         # Вспомогательные функции
├── data/                # Хранилище собранных данных и индекса
├── tests/               # Юнит-тесты
├── requirements.txt     # Зависимости
└── README.md            # Документация проекта
Лицензия
Лицензия MIT
Copyright (c) [Год] QinYou-Quantum (Qin Xiaoyou)
Разрешается свободно использовать, копировать, изменять, объединять, публиковать, распространять, сублицензировать и/или продавать копии данного ПО, а также разрешать лицам, которым предоставляется данное ПО, делать это при соблюдении следующих условий:
Указанное выше уведомление об авторском праве и это уведомление о разрешении должны быть включены во все копии или существенные части данного ПО.
ДАННОЕ ПО ПРЕДОСТАВЛЯЕТСЯ «КАК ЕСТЬ», БЕЗ КАКИХ-ЛИБО ГАРАНТИЙ, ЯВНЫХ ИЛИ ПОДРАЗУМЕВАЕМЫХ, ВКЛЮЧАЯ, НО НЕ ОГРАНИЧИВАЯСЬ, ГАРАНТИИ ТОВАРНОЙ ПРИГОДНОСТИ, ПРИГОДНОСТИ ДЛЯ ОПРЕДЕЛЕННОЙ ЦЕЛИ И НЕНАРУШЕНИЯ ПРАВ. НИ В КАКОМ СЛУЧАЕ АВТОРЫ ИЛИ ПРАВООБЛАДАТЕЛИ НЕ НЕСУТ ОТВЕТСТВЕННОСТИ ЗА ЛЮБЫЕ ПРЕТЕНЗИИ, УБЫТКИ ИЛИ ДРУГУЮ ОТВЕТСТВЕННОСТЬ, БУДЬ ТО В ДЕЙСТВИИ КОНТРАКТА, ДЕЛИКТЕ ИЛИ ИНОЙ ФОРМЕ, ВОЗНИКШИЕ ИЗ-ЗА ИСПОЛЬЗОВАНИЯ ПО ИЛИ СВЯЗАННЫЕ С ИСПОЛЬЗОВАНИЕМ ДАННОГО ПО.
Español
Descripción del Proyecto
Search-Engine es un proyecto personal de aprendizaje centrado en construir un prototipo simplificado de motor de búsqueda. Este proyecto cubre conceptos core de motores de búsqueda incluyendo rastreo web, indexación de datos, recuperación de palabras clave y algoritmos básicos de clasificación de resultados.
Características
Rastreador web básico para extracción de páginas estáticas
Implementación de índice invertido para búsqueda rápida de palabras clave
Clasificación simple de resultados basada en TF-IDF
API REST para interacción con consultas de búsqueda
Estructura de código ligera y fácil de extender
Stack Tecnológico
Lenguaje Principal: Python 3.8+
Librerías Core:
BeautifulSoup4 (análisis web)
Requests (solicitudes HTTP)
NLTK (procesamiento de texto)
Flask (servidor API)
Base de Datos: SQLite (para almacenamiento de índice)
Inicio Rápido
Requisitos Previos
bash
运行
pip install -r requirements.txt
Ejecutar el Motor de Búsqueda
bash
运行
# Iniciar rastreador para recopilar datos
python src/crawler.py --url https://example.com --depth 2

# Construir índice
python src/indexer.py

# Iniciar servidor API
python src/server.py

# Probar búsqueda
curl http://localhost:5000/search?q=tu_palabra_clave
Estructura del Proyecto
plaintext
Search-Engine/
├── src/
│   ├── crawler.py       # Módulo de rastreo web
│   ├── indexer.py       # Módulo de construcción de índice
│   ├── ranker.py        # Módulo de clasificación de resultados
│   ├── server.py        # Servidor API
│   └── utils.py         # Funciones auxiliares
├── data/                # Almacenamiento de datos rastreados e índice
├── tests/               # Pruebas unitarias
├── requirements.txt     # Dependencias
└── README.md            # Documentación del proyecto
Licencia
Licencia MIT
Copyright (c) [Año] QinYou-Quantum (Qin Xiaoyou)
Se concede permiso, de forma gratuita, a cualquier persona que obtenga una copia de este software y de los archivos de documentación asociados (el "Software"), para utilizar el Software sin restricción, incluyendo sin limitación los derechos a usar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar y/o vender copias del Software, y para permitir a las personas a las que se les proporcione el Software a hacerlo, sujeto a las siguientes condiciones:
El aviso de copyright anterior y este aviso de permiso se incluirán en todas las copias o partes sustanciales del Software.
EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A GARANTÍAS DE COMERCIABILIDAD, IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS AUTORES O TITULARES DEL COPYRIGHT SERÁN RESPONSABLES DE NINGUNA RECLAMACIÓN, DAÑOS U OTRA RESPONSABILIDAD, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE OTRO MODO, QUE SURJA DE O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTROS TRATOS EN EL SOFTWARE.
Français
Aperçu du Projet
Search-Engine est un projet personnel d'apprentissage axé sur la création d'un prototype simplifié de moteur de recherche. Ce projet couvre les concepts fondamentaux des moteurs de recherche, y compris le crawling web, l'indexation des données, la récupération de mots-clés et les algorithmes de classement de résultats basiques.
Fonctionnalités
Crawler web de base pour l'extraction de pages statiques
Implémentation d'un index inversé pour la recherche rapide de mots-clés
Classement simple des résultats basé sur TF-IDF
API REST pour l'interaction avec les requêtes de recherche
Structure de code légère et facile à étendre
Stack Technologique
Langage Principal: Python 3.8+
Bibliothèques Core:
BeautifulSoup4 (analyse web)
Requests (requêtes HTTP)
NLTK (traitement de texte)
Flask (serveur API)
Base de Données: SQLite (pour le stockage de l'index)
Démarrage Rapide
Prérequis
bash
运行
pip install -r requirements.txt
Lancer le Moteur de Recherche
bash
运行
# Démarrer le crawler pour collecter des données
python src/crawler.py --url https://example.com --depth 2

# Construire l'index
python src/indexer.py

# Démarrer le serveur API
python src/server.py

# Tester la recherche
curl http://localhost:5000/search?q=votre_mot_clef
Structure du Projet
plaintext
Search-Engine/
├── src/
│   ├── crawler.py       # Module de crawling web
│   ├── indexer.py       # Module de construction d'index
│   ├── ranker.py        # Module de classement des résultats
│   ├── server.py        # Serveur API
│   └── utils.py         # Fonctions auxiliaires
├── data/                # Stockage des données crawléées et de l'index
├── tests/               # Tests unitaires
├── requirements.txt     # Dépendances
└── README.md            # Documentation du projet
Licence
Licence MIT
Copyright (c) [Année] QinYou-Quantum (Qin Xiaoyou)
Permission est accordée, gratuitement, à toute personne obtenant une copie de ce logiciel et des fichiers de documentation associés (le « Logiciel »), de traiter le Logiciel sans restriction, y compris sans limitation les droits d'utiliser, de copier, de modifier, de fusionner, de publier, de distribuer, de sous-licencier et/ou de vendre des copies du Logiciel, et de permettre aux personnes à qui le Logiciel est fourni de le faire, sous réserve des conditions suivantes:
La notice de copyright ci-dessus et cette notice de permission doivent être incluses dans toutes les copies ou parties substantielles du Logiciel.
LE LOGICIEL EST FOURNI « TEL QUEL », SANS GARANTIE D'AUCUNE SORTE, EXPRESSE OU IMPLICITE, Y COMPRIS MAIS SANS LIMITATION LES GARANTIES DE QUALITÉ MARCHANDE, D'ADÉQUATION À UN USAGE PARTICULIER ET D'ABSENCE DE CONTREFAÇON. EN AUCUN CAS, LES AUTEURS OU TITULAIRES DU DROIT D'AUTEUR NE SERONT RESPONSABLES DE TOUTE RÉCLAMATION, DOMMAGES OU AUTRE RESPONSABILITÉ, QUE CE SOIT DANS LE CADRE D'UN CONTRAT, D'UN DÉLIT OU AUTRE, DÉCOULANT DE, OU EN RELATION AVEC LE LOGICIEL OU SON UTILISATION, OU AVEC D'AUTRES ÉCHANGES DANS LE LOGICIEL.
日本語
プロジェクト概要
Search-Engine は、簡易的な検索エンジンプロトタイプの構築に焦点を当てた個人の学習プロジェクトです。このプロジェクトは、ウェブクローリング、データインデックス作成、キーワード検索、基本的な結果ランキングアルゴリズムなどの検索エンジンのコアコンセプトをカバーしています。
機能
静的ページスクレイピング用の基本的なウェブクローラー
高速なキーワード検索のための逆インデックス実装
TF-IDF に基づくシンプルな結果ランキング
検索クエリインタラクション用の REST API
軽量で拡張が容易なコード構造
テクノロジースタック
プライマリ言語: Python 3.8+
コアライブラリ:
BeautifulSoup4 (ウェブ解析)
Requests (HTTP リクエスト)
NLTK (テキスト処理)
Flask (API サーバー)
データベース: SQLite (インデックスストレージ用)
クイックスタート
前提条件
bash
运行
pip install -r requirements.txt
検索エンジンの実行
bash
运行
# データ収集のためクローラーを起動
python src/crawler.py --url https://example.com --depth 2

# インデックスの構築
python src/indexer.py

# APIサーバーの起動
python src/server.py

# 検索のテスト
curl http://localhost:5000/search?q=キーワード
プロジェクト構造
plaintext
Search-Engine/
├── src/
│   ├── crawler.py       # ウェブクローリングモジュール
│   ├── indexer.py       # インデックス構築モジュール
│   ├── ranker.py        # 結果ランキングモジュール
│   ├── server.py        # APIサーバー
│   └── utils.py         # ヘルパー関数
├── data/                # クロールしたデータとインデックスストレージ
├── tests/               # ユニットテスト
├── requirements.txt     # 依存関係
└── README.md            # プロジェクトドキュメント
ライセンス
MIT ライセンス
Copyright (c) [年] QinYou-Quantum (Qin Xiaoyou)
本ソフトウェアおよび関連するドキュメントファイル（以下「ソフトウェア」）のコピーを取得するすべての人に対し、ソフトウェアの使用、コピー、変更、結合、発行、頒布、サブライセンス、および / または販売を制限なしに許可し、ソフトウェアが提供された人が同じことを行うことを許可する。ただし、次の条件に従うものとする。
上記の著作権表示および本許可表示は、ソフトウェアのすべてのコピーまたは実質的な部分に含まれなければならない。
本ソフトウェアは「現状有姿」で提供され、商品性、特定の目的への適合性、および非侵害に関する保証を含むがこれらに限定されない、いかなる明示的または黙示的な保証もなく提供される。いかなる場合も、著作権者または本ソフトウェアの提供者は、契約行為、不法行為、またはその他であろうと、ソフトウェアの使用またはその他の取引に起因または関連して生じるいかなる請求、損害、その他の責任についても責任を負わないものとする。
中文
项目概述
Search-Engine 是一个以学习为导向的轻量级搜索引擎原型项目，专注于构建简易的搜索引擎核心功能。本项目涵盖网络爬虫、数据索引、关键词检索、基础结果排序算法等搜索引擎核心概念。
核心功能
静态页面爬取的基础网络爬虫
实现倒排索引，支持快速关键词检索
基于 TF-IDF 的简易结果排序
提供搜索查询交互的 REST API
轻量且易于扩展的代码结构
技术栈
主开发语言：Python 3.8+
核心依赖库：
BeautifulSoup4（网页解析）
Requests（HTTP 请求）
NLTK（文本处理）
Flask（API 服务端）
数据库：SQLite（索引存储）
快速开始
环境准备
bash
运行
pip install -r requirements.txt
运行搜索引擎
bash
运行
# 启动爬虫采集数据
python src/crawler.py --url https://example.com --depth 2

# 构建索引
python src/indexer.py

# 启动 API 服务
python src/server.py

# 测试搜索接口
curl http://localhost:5000/search?q=你的关键词
项目结构
plaintext
Search-Engine/
├── src/
│   ├── crawler.py       # 网络爬虫模块
│   ├── indexer.py       # 索引构建模块
│   ├── ranker.py        # 结果排序模块
│   ├── server.py        # API 服务端
│   └── utils.py         # 辅助工具函数
├── data/                # 爬虫数据与索引存储目录
├── tests/               # 单元测试目录
├── requirements.txt     # 项目依赖清单
└── README.md            # 项目说明文档
许可证
MIT 许可证
版权所有 (c) [年份] QinYou-Quantum (秦晓尤)
兹免费授予任何获得本软件副本及相关文档文件（以下简称 “软件”）的人不受限制地处理该软件的权利，包括但不限于使用、复制、修改、合并、发布、分发、再许可和 / 或出售该软件副本的权利，以及授权接受该软件的人履行以下条件：
上述版权声明和本许可声明应包含在该软件的所有副本或主要部分中。
本软件按 “原样” 提供，不附带任何形式的明示或暗示的保证，包括但不限于对适销性、特定用途适用性和非侵权性的保证。在任何情况下，作者或版权持有人均不对因使用本软件或与本软件相关的任何索赔、损害或其他责任承担责任，无论是在合同诉讼、侵权诉讼或其他诉讼中，均不承担责任。
