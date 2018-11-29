NServiceBusExtensions is a collection of libraries that extend [NServiceBus](https://docs.particular.net/nservicebus/) in a variety of ways.


## License 

All projects are licensed under the [MIT](https://opensource.org/licenses/MIT)


<!--- StartOpenCollectiveBackers -->

## Community backed

**This is a community backed project. Backing is done via [opencollective.com/nservicebusextensions](https://opencollective.com/nservicebusextensions/).**

**It is expected that any developer that uses any of these libraries [become at least a backer](https://opencollective.com/nservicebusextensions#contribute).** This is an honesty system, there is no code that enforces. However when raising an issue or a pull request, the GitHub users name may be checked against [the list of backers](https://github.com/NServiceBusExtensions/Home/blob/master/backers.md), and that issue/PR may be closed without further examination.


### Backers

Thanks to all the backers! [[Become a backer](https://opencollective.com/nservicebusextensions#backer)]

[![OpenCollective](https://opencollective.com/nservicebusextensions/backers/badge.svg)](#backer)

<!--- EndOpenCollectiveBackers -->


### Licensing/Backing FAQ


#### But shouldn't OSS be completely free and supported by the community through their contributions?

Yes in theory this is true, however the long term reality has shown this not to be the case. The vast majority of consumers of open source projects do not contribute enough to ensure those project survive. This results in a small core team spending large amounts of their own free time maintaining projects.


#### But it is MIT, can't I use it for free?

Yes all projects are under [MIT](https://opensource.org/licenses/MIT) and you can ignore the community backing honesty system and use these project for free.


#### Do I need to be a backer to contribute a Pull Request?

Yes. You must be a backer to be a user of the below NuGet packages. Contributing Pull Requests does not cancel this out. It may seem unfair to expect people both contribute PRs and also financially back this project. However it is important to remember the effort in reviewing and merging a PR is often similar to that of creating the PR. Also the project maintainers are committing to support that added code (feature or bug fix) for the life of the project.


#### Do I need a license to use these libraries at runtime in production or testing environments?

No license is required on production systems.


#### Can I fork, re-use code, or start competing (possibly commercial) projects?

Yes.


#### Do all developers in a company need to become backers?

No. Only those coding against projects that directly, or indirectly, consume any of the NuGet packages listed below.


#### What happens if I wrap one of these libraries in another library?

Consumers of that wrapper should also become backers of NServiceBusExtensions.


### Reference material

 * [Open-Source Maintainers are Jerks!](https://vimeo.com/296579853)
 * [How to Charge for your Open Source](https://www.mikeperham.com/2015/11/23/how-to-charge-for-your-open-source/)
 * [Sustain OSS: The Report](https://sustainoss.org/assets/pdf/SustainOSS-west-2017-report.pdf)
 * [Open Source Maintainers Owe You Nothing](https://mikemcquaid.com/2018/03/19/open-source-maintainers-owe-you-nothing/)
 * [Who should fund open source projects?](https://jaxenter.com/who-funds-open-source-projects-133222.html)
 * [Apply at OSS Inc today](https://twitter.com/ryanchenkie/status/1067801413974032385)


# Extensions


## Logging


### [Serilog](https://github.com/NServiceBusExtensions/NServiceBus.Serilog)

Add support for sending NServiceBus logging message through [Serilog](https://serilog.net/).

[Documentation](https://docs.particular.net/nuget/NServiceBus.Serilog) | [NuGet](https://nuget.org/packages/NServiceBus.Serilog/)


### [MicrosoftLogging](https://github.com/NServiceBusExtensions/NServiceBus.MicrosoftLogging)

Add support for NServiceBus to log to [Microsoft.Extensions.Logging](https://github.com/aspnet/Logging).

[Documentation](https://docs.particular.net/nuget/NServiceBus.MicrosoftLogging) | [NuGet](https://nuget.org/packages/NServiceBus.MicrosoftLogging/)


## Serializers


### [Bond](https://github.com/NServiceBusExtensions/NServiceBus.Bond)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [Bond](https://microsoft.github.io/bond/manual/bond_cs.html).

[Documentation](https://docs.particular.net/nuget/NServiceBus.Bond) | [NuGet](https://nuget.org/packages/NServiceBus.Bond/)


### [Hyperion](https://github.com/NServiceBusExtensions/NServiceBus.Hyperion)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [Hyperion](https://github.com/akkadotnet/Hyperion).

[Documentation](https://docs.particular.net/nuget/NServiceBus.Hyperion) | [NuGet](https://nuget.org/packages/NServiceBus.Hyperion/)


### [Jil](https://github.com/NServiceBusExtensions/NServiceBus.Jil)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [Jil](https://github.com/kevin-montrose/Jil).

[Documentation](https://docs.particular.net/nuget/NServiceBus.Jil) | [NuGet](https://nuget.org/packages/NServiceBus.Jil/).


### [MsgPack](https://github.com/NServiceBusExtensions/NServiceBus.MsgPack)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [MsgPack](https://github.com/msgpack/msgpack-cli).

[Documentation](https://docs.particular.net/nuget/NServiceBus.MsgPack) | [NuGet](https://nuget.org/packages/NServiceBus.MsgPack/)


### [MessagePack](https://github.com/NServiceBusExtensions/NServiceBus.MessagePack)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [MessagePack-CSharp](https://github.com/neuecc/MessagePack-CSharp).

[Documentation](https://docs.particular.net/nuget/NServiceBus.MessagePack) | [NuGet](https://nuget.org/packages/NServiceBus.MessagePack/)


### [ProtoBufNet](https://github.com/NServiceBusExtensions/NServiceBus.ProtoBufNet)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [ProtoBufNet](https://github.com/mgravell/protobuf-net).

[Documentation](https://docs.particular.net/nuget/NServiceBus.ProtoBuf) | [NuGet](https://nuget.org/packages/NServiceBus.ProtoBuf/)


### [ProtoBufGoogle](https://github.com/NServiceBusExtensions/NServiceBus.ProtoBufGoogle)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [Google Protocol Buffers](https://developers.google.com/protocol-buffers/docs/reference/csharp-generated).

[Documentation](https://docs.particular.net/nuget/NServiceBus.ProtoBufGoogle) | [NuGet](https://nuget.org/packages/NServiceBus.ProtoBufGoogle/)


### [Utf8Json](https://github.com/NServiceBusExtensions/NServiceBus.Utf8Json)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [Utf8Json](https://github.com/neuecc/Utf8Json).

[Documentation](https://docs.particular.net/nuget/NServiceBus.Utf8Json) | [NuGet](https://nuget.org/packages/NServiceBus.Utf8Json/)


### [NServiceBus.Wire](https://github.com/NServiceBusExtensions/NServiceBus.Wire)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [Wire](https://github.com/rogeralsing/Wire).

[Documentation](https://docs.particular.net/nuget/NServiceBus.Wire) | [NuGet](https://nuget.org/packages/NServiceBus.Wire/)


### [ZeroFormatter](https://github.com/NServiceBusExtensions/NServiceBus.ZeroFormatter)

Add support for [message serialization](https://docs.particular.net/nservicebus/serialization/) via [ZeroFormatter](https://github.com/neuecc/ZeroFormatter).

[Documentation](https://docs.particular.net/nuget/NServiceBus.ZeroFormatter) | [NuGet](https://nuget.org/packages/NServiceBus.ZeroFormatter/)


## Validation


### [FluentValidation](https://github.com/NServiceBusExtensions/NServiceBus.Validation#nservicebusfluentvalidation)

Message validation using [FluentValidation](https://fluentvalidation.net/).

[Documentation](https://docs.particular.net/nuget/NServiceBus.DataAnnotations) | [Nuget](https://nuget.org/packages/NServiceBus.FluentValidation/) 


### [DataAnnotations](https://github.com/NServiceBusExtensions/NServiceBus.Validation#nservicebusdataannotations)

Message validation using [DataAnnotations](https://docs.microsoft.com/en-us/dotnet/api/system.componentmodel.dataannotations).

[Documentation](https://docs.particular.net/nuget/NServiceBus.DataAnnotations) | [NuGet](https://nuget.org/packages/NServiceBus.DataAnnotations/)


## Attachments


### [Sql Attachments](https://github.com/NServiceBusExtensions/NServiceBus.Attachments#sql)

An implementation of the claim check pattern against SQL server.

[Documentation](https://docs.particular.net/nuget/NServiceBus.Attachments.Sql) | [NuGet](https://nuget.org/packages/NServiceBus.Attachments.Sql/)


### [FileShare Attachments](https://github.com/NServiceBusExtensions/NServiceBus.Attachments#FileShare)

An implementation of the claim check pattern against a network file share.

[Documentation](https://docs.particular.net/nuget/NServiceBus.Attachments.FileShare) | [NuGet](https://nuget.org/packages/NServiceBus.Attachments.FileShare/)


## Misc


### [Sql Transport  Native](https://github.com/NServiceBusExtensions/NServiceBus.Native#sqlservernative)

SQL Server Transport Native is a shim providing low-level access to the [SQL Server Transport](https://docs.particular.net/transports/sql/) with no NServiceBus or SQL Server Transport reference required. 

[Documentation](https://nuget.org/packages/NServiceBus.SqlServer.Native) | [NuGet](https://nuget.org/packages/NServiceBus.SqlServer.Native/)


### [Sql Transport HttpPassthrough](https://github.com/NServiceBusExtensions/NServiceBus.Native#sqlserverhttppassthrough)

SQL HTTP Passthrough provides a bridge between an HTTP stream (via JavaScript on a web page) and the [SQL Server transport](https://docs.particular.net/transports/sql/). It leverages [SQL Transport - Native](https://docs.particular.net/transports/sql/sql-native.md) and [SQL Attachments](https://docs.particular.net/nservicebus/messaging/attachments-sql.md).

[Documentation](https://docs.particular.net/nuget/NServiceBus.SqlServer.HttpPassthrough) | [NuGet](https://nuget.org/packages/NServiceBus.SqlServer.HttpPassthrough/)


### [HandlerOrdering](https://github.com/NServiceBusExtensions/NServiceBus.HandlerOrdering)

Allows the dependency between handlers to be expressed via interfaces and the resulting order is derived at runtime.

[Documentation](https://docs.particular.net/nuget/NServiceBus.HandlerOrdering) | [NuGet](https://nuget.org/packages/NServiceBus.HandlerOrdering/)


### [AuditFilter](https://github.com/NServiceBusExtensions/NServiceBus.AuditFilter)

Selectively choose what message types should be sent to the [Audit queue](https://docs.particular.net/nservicebus/operations/auditing).

[Documentation](https://docs.particular.net/nuget/NServiceBus.AuditFilter) | [NuGet](https://nuget.org/packages/NServiceBus.AuditFilter/)


### [Newtonsoft Message Property Encryption](https://github.com/NServiceBusExtensions/Newtonsoft.Json.Encryption#nservicebus)

Leverages the Newtonsoft extension API to encrypt/decrypt specific parts of messages at serialization time.

[Documentation](https://docs.particular.net/samples/encryption/newtonsoft-json-encryption/) | [NuGet](https://www.nuget.org/packages/NServiceBus.Newtonsoft.Encryption/)