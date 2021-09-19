# FlowerGam0326

## 꽃감이 트위치 방송 알림 프로그램 ( 디스코드 웹훅 or 프로그램 알림)

[![Twitch Status](https://img.shields.io/twitch/status/flowergam0326?label=%EA%BD%83%EA%B0%90%EC%9D%B4&style=social)](https://www.twitch.tv/flowergam0326)
[![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCIiAsSxd21ZGabut95VYYgw?label=Sing%20Youtube&style=social)](https://www.youtube.com/channel/UCIiAsSxd21ZGabut95VYYgw)
[![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCvFBlZPInHWf8eE4WUkKS6A?label=Sub%20Youtube&style=social)](https://www.youtube.com/channel/UCvFBlZPInHWf8eE4WUkKS6A)
[![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCX3ELg-sB0Y3pWpOVIW8CpA?label=JP%20Youtube&style=social)](https://www.youtube.com/channel/UCX3ELg-sB0Y3pWpOVIW8CpA)

* [트위치 바로가기](https://www.twitch.tv/flowergam0326)
* [노래 유튜브](https://www.youtube.com/channel/UCIiAsSxd21ZGabut95VYYgw)
* [서브 유튜브](https://www.youtube.com/channel/UCvFBlZPInHWf8eE4WUkKS6A)
* [JP 유튜브](https://www.youtube.com/channel/UCX3ELg-sB0Y3pWpOVIW8CpA)
* [인스타그램](https://www.instagram.com/flowergam/)

----

### 기능

* 트위치 Live 확인
    > 트위치 API를 통해 방송중인지 확인합니다.

* 디스코드 웹훅으로 알림 보내기
    > 라이브 방송이 확인되면 디스코드 웹훅 링크를 통해 알림을 전송합니다.

  * ![Discord-Webhook][Discord-Webhook-Ex]

### 요구 사항

* [.NET Framework 4.7.2 버전이 필요합니다.](https://dotnet.microsoft.com/download/dotnet-framework/net472)
* 디스코드 웹훅 링크가 필요합니다.
* 트위치 API 토큰이 필요합니다. [트위치 API DOC](https://dev.twitch.tv/docs/api/)

**패키지** | **라이선스**
-------- | ----------------------------------------------------------
[![Discord.Net.Core](https://img.shields.io/nuget/v/Discord.Net.Core?label=Discord.Net.Core&logo=NuGet)](https://www.nuget.org/packages/Discord.Net.Core) | [![Discord.Net][DiscordNetLicense]](https://licenses.nuget.org/MIT)
[![Discord.Net.Rest](https://img.shields.io/nuget/v/Discord.Net.Rest?label=Discord.Net.Rest&logo=NuGet)](https://www.nuget.org/packages/Discord.Net.Rest) | [![Discord.Net][DiscordNetLicense]](https://licenses.nuget.org/MIT)
[![Discord.Net.Webhook](https://img.shields.io/nuget/v/Discord.Net.Webhook?label=Discord.Net.Webhook&logo=NuGet)](https://www.nuget.org/packages/Discord.Net.Webhook) | [![Discord.Net][DiscordNetLicense]](https://licenses.nuget.org/MIT)
[![Newtonsoft.Json](https://img.shields.io/nuget/v/Newtonsoft.Json?label=Newtonsoft.Json&logo=NuGet)](https://www.nuget.org/packages/Newtonsoft.Json) | [![Newtonsoft.Json][NewtonsoftJsonLicense]](https://licenses.nuget.org/MIT)
[![Costura.Fody](https://img.shields.io/nuget/v/Costura.Fody?label=Costura.Fody&logo=NuGet)](https://www.nuget.org/packages/Costura.Fody/) | [![Costura.Fody][CosturaFodyLicense]](https://licenses.nuget.org/MIT)

----

### 라이선스

* CCL ([크리에이티브 커먼즈 라이선스](https://en.wikipedia.org/wiki/Creative_Commons_license))
* BY-NC-SA (저작자표시 + 비영리 + 동일조건변경허락)
* ![BY-NC-SA][CCL-BY-NC-SA]

### K1649c

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FK1649c%2FFlowerGam0326&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

[Discord-Webhook-Ex]: ./img/Discord-2.png "디스코드 웹훅 메세지 예시 이미지"
[CCL-BY-NC-SA]: https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Cc-by-nc-sa_icon.svg/120px-Cc-by-nc-sa_icon.svg.png "CCL BY-NC-SA 라이센스 이미지"
[DiscordNetLicense]: https://img.shields.io/github/license/Discord-Net/Discord.Net
[NewtonsoftJsonLicense]: https://img.shields.io/github/license/JamesNK/Newtonsoft.Json
[CosturaFodyLicense]: https://img.shields.io/github/license/Fody/Costura
