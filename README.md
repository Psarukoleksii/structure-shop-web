# General structure for web-shop

## Folders structure

In general, I suggest to use `MVC` (Model-View-Controller) design pattern in this project. 

`Model`. All our models will be in separate hooks, for example `useProducts`, `useCategories`, `useUsers`, `useCustomers` and so on. And in this hooks will be everything, what is linked with this specific entity.

`View` - will be our organisms, which will be responded for showing proper molecule or atom components.

`Controller` - this functionality will be on page, business logic, calculations, manipulations with data and so on.

## API

In API folder I suggest to configure everything what is linked with calls to server side.

## Assets

Folder for icons, logo, images etc...

## Components

Split our components by atoms/molecules/organisms/templates. Atomic architecture for this.

## Configs

Everything what is linked with config: app paths, format time and timezones, acceptable video formats/images and so on.

## Hooks

General hooks, which will be responded for general things, for example: check out some permissions, private rules, notifications and so on.

## Contexts

Folder for keeping context with cart, permissions and so on

## Interfaces

General interfaces for common usage: pagination data, server error response, file interface... which will be not linked with models

## Models

Our models will be splited by entity: user, product, customers and so on. Everything, which will be linked with this entity - will be in this folder. Mappers, interfaces, utils, configs, enums and so on. Everything, what is linked with manipulations with this data of entity. 

## Pages

Our controllers, on pages will be decide about calls to separate models, manipulations with data and so on.

## Utils

General utils, which be not linked with our models 
