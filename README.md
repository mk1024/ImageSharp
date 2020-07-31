# Using ImageSharp commercially under AGPL

(Please refer to [SixLabors/ImageSharp](https://github.com/SixLabors/ImageSharp) for the latest version and the most recent [README](https://github.com/SixLabors/ImageSharp/blob/master/README.md).)

## Disclaimer

- The following information about using AGPL licensed software in a commercial context represents my own thoughts on the GNU AGPL license and related statements of the Free Software Foundation. I tried to keep it short to focus on the most important points. Please read the license carefully to determine which obligations arise from your intended use.
- This information was put together because there are some misconceptions about using ImageSharp or other AGPL projects in a commercial context. If you can use ImageSharp according to the AGPL license, then there is nothing wrong about it. If, however, your intended use is not covered by the AGPL, you should pay for the commercial license and support the many contributors of this project.

## Update (Jun 08, 2020)
  
- ImageSharp has returned to the Apache license. The restrictions of the AGPL license mentioned below do not longer apply.

## ImageSharp Licensing (as of May 25, 2020)
  
- ImageSharp is licensed under the [GNU Affero General Public License v3 (AGPL)](https://www.gnu.org/licenses/agpl-3.0).
- An alternative [Commercial License can be purchased](https://sixlabors.com/pricing) for Closed Source projects and applications.
- Existing Open Source projects may get permission to continue using ImageSharp under the previous [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).

## Key difference between GPL/AGPL

- The **GPL** basically requires you to make your modifications available to all your end users. If your software uses a modified version of a GPL licensed software and you deploy this software to your end users, all your end users must be able to access these modifications.
- This opens the so called **ASP loophole**: If the modified software only runs on a server and is not deployed to end users, there is no need to make modifications available to the users.
- The **AGPL** closes this loophole by extending the definition of users: If you run the modified software on a server and let remote users interact with this software, you have to give these users access to your modifications.

## How can you use AGPL licensed software?

- **Distribution** with your closed source product: Whenever you distribute a modified version of GPL/AGPL licensed software, you have to put your software under the GPL/AGPL and make the source code available to your end users.
- **Hosting** a service that is accessed by remote users: In contrast to the GPL, the AGPL kicks in even if the modified software is not actually deployed to the end users. You have to put your software under a compatible license and give users access to your modifications. [1][2]
- **Internal** use within an organization: When there are no end users interacting with the software, there are no end users who must get access to the (modified) source code. An Organization may modify the AGPL licensed software and use it internally without being required to put own software under the AGPL. The AGPL does, however, not allow the distribution of copies to other organizations or individuals. [3][4]
- **Output** of GPL licensed software: If you create or modify an image with GPL/AGPL software, the saved image just inherits the copyright status of the original image. In the sense of copyright the saved image is not a derived work based on the software. You can use the modified image just the same as the original image. [5][6]

Free Software Foundation GPL/AGPL FAQ:

- [1] [[...] running a modified version of a GPLed program on a web site [...]](https://www.gnu.org/licenses/gpl-faq.html#UnreleasedMods)
- [2] [[...] modified version of a program licensed under the GNU Affero GPL [...]](https://www.gnu.org/licenses/gpl-faq.html#UnreleasedModsAGPL)
- [3] [[...] without distributing or conveying them to others [...]](https://www.gnu.org/licenses/gpl-faq.html#NoDistributionRequirements)
- [4] [[...] copies within one organization or company [...]](https://www.gnu.org/licenses/gpl-faq.html#InternalDistribution)
- [5] [[...] GPL the output people get from use of my program?](https://www.gnu.org/licenses/gpl-faq.html#GPLOutput)
- [6] [[...] is the output of a GPL program covered by the GPL too?](https://www.gnu.org/licenses/gpl-faq.html#WhatCaseIsOutputGPL)
