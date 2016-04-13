Slant LINQ
==============

[![Join the chat at https://gitter.im/slantdotnet/Slant.Entity](https://badges.gitter.im/slantdotnet/Slant.Entity.svg)](https://gitter.im/slantdotnet/Slant.Entity?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![NuGet version (Slant.Entity)](https://img.shields.io/nuget/v/Slant.Entity.svg?style=flat)](https://www.nuget.org/packages/Slant.Entity/)
[![Build Status](https://travis-ci.org/slantdotnet/Slant.Entity.svg?branch=master)](https://travis-ci.org/slantdotnet/Slant.Entity)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/slantdotnet/Slant.Entity/master/license.txt)

## Overview

Slant.Linq is a free set of extensions for LINQ and Entity Framework power users. It comprises the following:

* An extensible implementation of AsExpandable()
* A public expression visitor base class (ExpressionVisitor)
* PredicateBuilder
* Linq.Expr and Linq.Func shortcut methods

With Slant.Linq, you can:

* Plug expressions into EntitySets and EntityCollections
* Use expression variables in subqueries
* Combine expressions (have one expression call another)
* Dynamically build predicates
* Leverage AsExpandable to add your own extensions.

## Installation

We recommended installing [the NuGet package](https://www.nuget.org/packages/Slant.Linq). Install on the command line from your solution directory or use the Package Manager console in Visual Studio:

```powershell

PM> Install-Package Slant.Linq

```

## Usage

Check out our wiki to see typical and non-trivial usages and detailed examples:

[Using LINQ Extensions](https://github.com/slantdotnet/Slant.Entity/wiki/Using-LINQ-Extensions)

[Using DbContextScope](https://github.com/slantdotnet/Slant.Entity/wiki/Using-DbContextScope)

## Contributing

Check out [this wiki page](https://github.com/slantdotnet/Slant.Entity/wiki/Contributing) for complete guide.

## Thanks to

Jetbrains Community Support for providing great tools for our team

[![Jetbrains Resharper](http://nspectator.org/assets/icon_ReSharper.png)](https://www.jetbrains.com/resharper/)


