---
title: Minecraft Definitions
---

# MCDefinitions

This file specifies anything that is included in the project, but cannot be found in the project files itself, or not easly. At the same time the user can also exclude definitions
through this same project. Make sure the file is located at the root of your workspace and named: `.mcdefinitions`

**Example**

```ini
## I am a comment

## Tags used in the map
tag=initialized
tag=calculating
tag=enemy
tag=monster


## Tags to be excluded
tag=!Monster

## Objectives used in the map
objective=var
objective=coin
objective=foo

## Objectives excluded
objective=!Var
objective=!Coin

## Families
family=npc

## Families excluded
family=!Npc

## Entity names
name=Steve

## Entity names excluded
name=!steve
```

## Properties

This plugin looks and processes the following definitions

| name      | description |
| --------- | ----------- |
| tag       |             |
| objective |             |
| name      |             |
| family    |             |
