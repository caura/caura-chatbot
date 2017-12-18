# Language AI
This is a native interface to an alpha version of a Language ML API service.

In its simplified form, this is an expanded version of Maximum likelihood model called Max Entropy:<br/>
<center><img width="300" src="https://user-images.githubusercontent.com/1756903/32816722-17b7e470-c96f-11e7-8225-9ee0e0882343.png"></center>

## R Examples (release date: TBD):
```r
library(languageML)
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

Demo is in the chat interface.

**Steps:**

1. Register a new temporary user on [app.wire.com](https://app.wire.com/auth/#register) of no affiliation
2. Follow all the usual wire's activation procedures *(i.e. email confirmation - Sorry!)*
3. Enable the bot by clicking here: [caura.co/entropy-ai](https://www.caura.co/entropy-ai)

*(Non-IE/Chrome users: please allow 3rd party cookies under Cookie Control)*

## How To Stay Up To Date

**EQ engine** - updates are handled by Caura & Co.<br>
**Wire SDK** - see Wire link above for this git repo for updates to their SDK<br>
**Availability** - the server running LanguageRml service cannot currently handle large volumes. You might experience some of our throttling until we distribute the workload 

## About / Contributions

[@segahm](https://github.com/segahm) - this bot<br/>
[Caura & Co. Team](https://github.com/caura) - Language.Ml<br/>
[@dkovacevic](https://github.com/dkovacevic) - Wire dev. support and troubleshooting<br/>

**"Places where linguists traditionally look to see [entropy] are not where the fundamentals of language are."**<br/>
*Marcelo A. Montemurro and Damián H. Zanette*

![Caura & Co.](https://media.giphy.com/media/3ov9jWL0UzwzwvsPTi/giphy.gif "telephone operators")
