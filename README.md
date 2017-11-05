<a href="https://www.gnu.org/licenses/gpl-3.0" target="_blank"><img src="https://img.shields.io/badge/License-GPL%20v3-blue.svg" alt="License: GPL v3"/></a><br/>
# Language R ML
This is a native interface to an alpha version of a Language ML API service.

In its simplified form, this is an expanded version of Maximum likelihood model called Max Entropy:<br/>
<center><img width="300" src="https://user-images.githubusercontent.com/1756903/32816722-17b7e470-c96f-11e7-8225-9ee0e0882343.png"></center>

## R Examples (release date: TBD):
```r
library(languageRml)
entropy('Hello, we are on a mission to change written communication.')
```

```r
## [1] "Result"        "driven"        "Passive voice" "Concise"      
## [5] "Informal"      "Thoughtful"    "Assertive"
```

```r
entropy("Don't get us wrong, we love existing tools such as Gmail and Slack. Yet, we believe that our communication is poor (Emojis - come on...). We are capable of much more!")
```

```r
## [1] "Thoughtful" "Inormal"   "Verbose"
```

## Architecture

<img width="700" src="https://user-images.githubusercontent.com/1756903/34074096-dda47fee-e25c-11e7-91dc-b60cf94b326a.png">

## Try It Now

We see most useful use cases for this arise in chat/email correspondence, so **demo is done through a chat interface** as well (Wire company is of no affiliation - just using them as an alternative to popular social media apps).

**Steps:**

1. Register a new temporary user on [app.wire.com](https://app.wire.com/auth/#register)
2. Follow all the usual wire's activation procedures *(i.e. email confirmation - Sorry!)*
3. Enable the bot by clicking here: [caura.co/entropy-ai](https://www.caura.co/entropy-ai)

*(Non-IE/Chrome users: please allow 3rd party cookies under Cookie Control)*

## How To Stay Up To Date

**EQ engine** - updates are handled by Caura & Co.<br>
**Wire SDK** - see Wire link above for this git repo for updates to their SDK<br>
**Availability** - the server running LanguageRml service cannot currently handle large volumes. You might experience some of our throttling until we distribute the workload 

## About / Contributions

[Caura & Co. Team](https://github.com/caura) - Language.Rml + Bot dev. work<br/>
[@dkovacevic](https://github.com/dkovacevic) - Wire dev. support and troubleshooting<br/>

**"Places where linguists traditionally look to see [entropy] are not where the fundamentals of language are."**<br/>
*Marcelo A. Montemurro and Damián H. Zanette*

![Caura & Co.](https://media.giphy.com/media/3ov9jWL0UzwzwvsPTi/giphy.gif "telephone operators")