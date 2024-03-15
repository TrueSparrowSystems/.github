# About True Sparrow
True Sparrow is a boutique product development studio providing software engineering and design services. We work with clients to rapidly turn their ideas into live scalable products. We occasionally build in-house moonshots as well.

# Our Open Source Products
We not only help our clients take things from 0 to 1, but we also enjoy giving back to the community through our contributions to Open Source. Here are some of our Open Source contributions.

## Needle in a Haystack
We are actively contributing, enhancing and co-maintaining Needle in a Haystack (NIAH) along with [Greg Kamradt](https://github.com/gkamradt) (original author). NIAH is a technique used to benchmark Large Language Models (LLMs). In this technique, the model's objective is to locate particular information (referred to as the "needle") within a broader context (referred to as the "haystack"). Initially introduced by Greg for GPT-4 and Claude 2.1, this evaluation has garnered widespread recognition, being embraced by Google for [Gemini 1.5](https://blog.google/technology/ai/google-gemini-next-generation-model-february-2024/#performance:~:text=Gemini%201.5%20Pro%20maintains,as%201%20million%20tokens) and by Anthropic for [Claude 3](https://www.anthropic.com/news/claude-3-family#:~:text=the%20'needle%20in%20a%20haystack'%20(niah)%20evaluation%20measures%20a%20model's%20ability%20to%20accurately%20recall%20information%20from%20a%20vast%20corpus%20of%20data).

Repo(s): [Needle in a Haystack](https://github.com/gkamradt/LLMTest_NeedleInAHaystack)
## Prompt Evaluator
The Prompt Evaluator is a test suite that helps evaluate prompt templates and AI models. It enables Product Managers and Developers to create prompt templates with custom variables, define test cases with specific variable values and expected responses, and match the generated responses exactly or fuzzily. The suite also allows for comparing GraphQL query responses and measuring the accuracy of prompt templates against different AI models. By leveraging the capabilities of the Prompt Evaluator, Product Managers and Developers can make informed decisions, iterate on their prompt designs, and enhance the overall quality and accuracy of their AI-powered applications.

Repo(s): [Prompt Evaluator Frontend](https://github.com/TrueSparrowSystems/prompt-eval-fe), [Prompt Evaluator Backend](https://github.com/TrueSparrowSystems/prompt-eval-be)

## UniCache
UniCache is an open-source NPM package that offers a unified and consistent interface for Memcached, Redis, and in-memory caching. It simplifies the interaction with multiple caching engines, reducing development time and effort. UniCache is also fully compatible with AWS ElastiCache for Memcached and Redis.

Repo(s): [UniCache](https://github.com/TrueSparrowSystems/UniCache)

## Applogger
AppLogger is a React Native mobile application framework that reduces QA issue-reporting time and developer debugging time. It provides a web interface for logs generated and user steps taken on a device using the device's IP address. Users can track their sessions and logs, as well as upload, download, and delete them.

Repo(s): [AppLogger](https://github.com/TrueSparrowSystems/applogger)

## Slackmin
Slackmin streamlines Slack integration in Node.js applications by enabling custom tool creation to manage content, orders, reports, customers, and more. Features include slash commands, interactive components, message formatting, and custom modals. Additionally, critical event alerts and notifications can be sent via Slack.

Repo(s): [Slackmin](https://github.com/TrueSparrowSystems/slackmin)

## Canary
Canary is a cross-platform mobile application that allows users to discover and save content via Twitter APIs without requiring an account or login information. All data is private and stored on the user's device without tracking parameters.

Repo(s): [Canary](https://github.com/TrueSparrowSystems/canary)

## Queue
Queue simplifies publishing and subscribing tasks over RabbitMQ by utilizing a topic-based exchange. One use case is API worker processes to publish tasks for asynchronous processing, which can then be picked up by subscribed worker processes.

Repo(s): [Queue](https://github.com/TrueSparrowSystems/queue)

## NFT or NOT
NFT or NOT is a social experiment built on Lens Protocol, transforming the 2000s craze Hot-or-Not into a thrilling showdown of AI-generated images based on community prompts. Users can collect NFTs for a fee to support creators, and the highest-voted submission makes it to the Hall of Flame.

Repo(s): [NFT or NOT Frontend](https://github.com/TrueSparrowSystems/nft-or-not-fe), [NFT or NOT Backend](https://github.com/TrueSparrowSystems/nft-or-not-be)

## Whisper Chain
Whisper Chain is a fun social experiment built on Lens Protocol, where users can experience the thrill of chain mutations. It is based on the classic game of Chinese whispers or telephone, where the objective is to observe how much the original seed image changes as it gets passed along the chain.

Repo(s): [Whisper Chain Frontend](https://github.com/TrueSparrowSystems/whisper-chain-fe), [Whisper Chain Backend](https://github.com/TrueSparrowSystems/whisper-chain-be)

## Openapi Test Suite
Openapi Test Suite simplifies the creation and maintenance of API test suites by using an Openapi.json API specification file to generate test cases automatically. This method is compatible with APIs written in any programming language, as long as the Openapi.json file is available.

Repo(s): [Openapi Test Suite](https://github.com/TrueSparrowSystems/openapi-test-suite)

## Base
Base is a collection of frequently used functionalities in True Sparrow repositories, such as a custom logger, response helper, Promise QueueManager, and Instance composer. It standardizes logging and response formatting across applications, and the QueueManager provides management options and configurations for a queue of Promises. The Instance composer facilitates the sharing of config strategies across registered classes and instances.

Repo(s): [Base](https://github.com/TrueSparrowSystems/base)

## OpenST and OST
OpenST is an open-source framework for deploying scalable token economies. The project has released two protocols:
- OpenST for minting Brand Tokens (utility tokens) on layer-2 Ethereum blockchains by staking ERC-20 assets (value tokens) on layer-1 Ethereum
- Mosaic for proving layer-2 transactions at scale back on layer-1

Furthermore, OST technology enables developers to seamlessly embed Ethereum wallets into mainstream applications to benefit from zero-fee micro-transactions.

Repo(s): [OpenST](https://github.com/orgs/OpenST/repositories), [OST](https://github.com/orgs/ostdotcom/repositories)

# Popular Open Source Libraries We Contributed To
- React Native
    - [Feature: Added enterKeyHint prop to textInput](https://github.com/facebook/react-native/pull/34482)
    - [Feature: Added userSelect style equivalent to selectable](https://github.com/facebook/react-native/pull/34575)
    - [Feature: Added aria-modal as alias for accessibilityViewIsModal(iOS)](https://github.com/facebook/react-native/pull/34506)
    - [Feature: Added crossOrigin, referrerPolicy, srcSet, width, height and src props to the Image Component.](https://github.com/facebook/react-native/pull/34481)
    - [Feature: Added accessibility value aliases](https://github.com/facebook/react-native/pull/34535)
    - [Extracted IncorrectModuleRegistryCallTypeParameterParserError to throwIfIncorrectModuleRegistryCallTypeParameterParserError](https://github.com/facebook/react-native/pull/34941)
- The Algorithms - JavaScript
    - [Added new algorithm: first unique char in a string](https://github.com/TheAlgorithms/JavaScript/pull/1103)
    - [Added new algorithm: countSubstrings function implementation](https://github.com/TheAlgorithms/JavaScript/pull/1091)
    - [Added new algorithm: find the middle of linked-list](https://github.com/TheAlgorithms/JavaScript/pull/1096)
    - [Bug fix: Cycledetection.js and added tests](https://github.com/TheAlgorithms/JavaScript/pull/1099)
    - [Bug fix: RotateListRight.js and added tests](https://github.com/TheAlgorithms/JavaScript/pull/1101)
- Sanitize HTML
    - [Handling of invalid markup: closing tags without having opening tags](https://github.com/apostrophecms/sanitize-html/pull/568)
    - [For allowedTags, stop treating falsy values other than false, same as false.](https://github.com/apostrophecms/sanitize-html/pull/577)
    - [Upgrades htmlparser2 to new major version ^8.0.0.](https://github.com/apostrophecms/sanitize-html/pull/573)
- MLflow
    - [Added MlflowException on top level](https://github.com/mlflow/mlflow/pull/6687)
    - [Used tuple instead a comma-separated string in pytest.mark.parametrize](https://github.com/mlflow/mlflow/pull/6623)
    - [Added padding to artifact text viewer](https://github.com/mlflow/mlflow/pull/6778)
- FX-FOTOS
    - [Single image viewer feature](https://github.com/functionland/fx-fotos/pull/239)
    - [Single image viewer gesture improvements](https://github.com/functionland/fx-fotos/pull/272)
- React Native Paper
    - [Fix: Button ripple radius](https://github.com/callstack/react-native-paper/pull/3388)
- Prefect
    - [Used anyio.abc full namespace instead of from imports](https://github.com/PrefectHQ/prefect/pull/6784)
- Luxon
    - [Bug fix: DateTime.diff produces wrong results with unit quarter](https://github.com/moment/luxon/pull/1279)
- GO Package Validator
    - [Bug fix: Fixed boolean validation to handle bool kind](https://github.com/go-playground/validator/pull/988)
- Croc
    - [Added zstd as a compression algorithm](https://github.com/schollz/croc/pull/506)
- Mimetype
    - [Added support for JXS file format](https://github.com/gabriel-vasile/mimetype/pull/319)
