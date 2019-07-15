# CAP

<img height="140" align="right" src="https://cap.dotnetcore.xyz/img/logo.svg">
[![Travis branch](https://img.shields.io/travis/dotnetcore/CAP/master.svg?label=travis-ci)](https://travis-ci.org/dotnetcore/CAP)
[![AppVeyor](https://ci.appveyor.com/api/projects/status/v8gfh6pe2u2laqoa/branch/master?svg=true)](https://ci.appveyor.com/project/yuleyule66/cap/branch/master)
[![NuGet](https://img.shields.io/nuget/v/DotNetCore.CAP.svg)](https://www.nuget.org/packages/DotNetCore.CAP/)
[![NuGet Preview](https://img.shields.io/nuget/vpre/DotNetCore.CAP.svg?label=nuget-pre)](https://www.nuget.org/packages/DotNetCore.CAP/)
[![Member project of .NET Core Community](https://img.shields.io/badge/member%20project%20of-NCC-9e20c9.svg)](https://github.com/dotnetcore)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/dotnetcore/CAP/master/LICENSE.txt)

CAP is a library based on .Net standard, which is a solution to deal with distributed transactions, also has the function of EventBus, it is lightweight, easy to use, and efficiently.

## Introduction

In the process of building an SOA or MicroService system, we usually need to use the event to integrate each services. In the process, the simple use of message queue does not guarantee the reliability. CAP is adopted the local message table program integrated with the current database to solve the exception may occur in the process of the distributed system calling each other. It can ensure that the event messages are not lost in any case.

You can also use the CAP as an EventBus. The CAP provides a simpler way to implement event publishing and subscriptions. You do not need to inherit or implement any interface during the process of subscription and sending.

!!! Tip "CAP implements the Outbox Pattern described in the [eShop ebook](https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/multi-container-microservice-net-applications/subscribe-events#designing-atomicity-and-resiliency-when-publishing-to-the-event-bus)"
    <img src="img/architecture-eshop.png">

    > Atomicity when publishing events to the event bus with a worker microservice


For detailed instructions see the [Getting Started Guide][1].

  [1]: user-guide/en/getting-started/quick-start.md

## Contributing

One of the easiest ways to contribute is to participate in discussions and discuss issues. You can also contribute by submitting pull requests with code changes.

If you have any question or problems, please report them on the CAP repository:

<a href="https://github.com/dotnetcore/cap/issues/new"><button data-md-color-primary="purple"><i class="fa fa-github fa-2x"></i> Report Issue</button></a>
<a href="https://github.com/dotnetcore/cap/issues"><button data-md-color-primary="purple" type="submit"> Active Issues <i class="fa fa-github fa-2x"></i></button></a>

## License

CAP is licensed under the [MIT license](about/license.md).