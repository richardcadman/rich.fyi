---
layout: post
title:  "Broken banking - some learnings"
date:   2018-10-10 15:59:18 +0100
categories: general
---

`Some learnings from the time I removed my overdraft on Natwest.`

<br>

## Disclaimer, I'm building a bank at Monzo

Full disclaimer, I'm a Product Manager at [Monzo](https://monzo.com/). Monzo's a UK challenger bank that lives on your smartphone.

## I recently turned off my overdraft with Natwest

Control matters a lot, particularly when it comes to money, so I'm always on the lookout for where we can improve this part of the banking experience.

I don't use my Natwest account as often as I used to, so I turned off my overdraft
- For peace of mind
- To avoid accidental charges (this later proved futile)
- To learn some stuff

## It was an awful experience but I learnt some stuff

I had a frustrating, shitty experience. But, in the process, I learnt some basic principles:
1. **Minimise steps in the process, and avoid asking for unnecessary information**
2. **Give people what they ask for (i.e. no overdraft charges if I've removed my overdraft)**
3. **Get the basic technology right (instant, mobile first, single browser, error handling)**

Read on for more.


<br>

___
## Here's some learnings

### :zap: 1. Make it in-app, in one place, and instant

![overdrafts](/assets/img/natwest/natwest_six_small_popup.png){:class="img-responsive"}

- I'm set up for mobile banking so I tried there first, unsuccessfully
- I have to open three browser windows in total - try to keep things in one place if you can
- If you insist on opening something new, multiple tabs are better than multiple browsers
- Ideally, removing my overdraft should be immediate too

### :massage: 2. Make it simple, and avoid unnecessary steps

![overdrafts](/assets/img/natwest/natwest_five_process.png){:class="img-responsive"}

- Don't make me fill out a form to _'apply for an overdraft'_ (I don't want one, I'm trying to remove an overdraft :information_desk_person:)
- Tell me why you need information, or don't ask for it (three previous addresses :expressionless: ?)
- Thumbs up for accessibility though

### :question: 3. Be specific, or explain why you can't be

- Natwest tell me that my request be actioned _'as soon as they can'_
- Vague timelines are really frustrating, so try to be specific when you can
- If that's not possible, explain why it's the case

### :floppy_disk: 4. Use 'normal' communication methods   

![overdrafts](/assets/img/natwest/natwest_ten_confirmation_letter.png){:class="img-responsive"}

- Ideally I'd have got instant confirmation that my overdraft was removed
- If a delay is unavoidable, just send me a quick text later saying it's all sorted :thumbsup:
- Instead, a day or so after 'applying' I get an email that invites me to log back in and view the results of my overdraft application (tension is killing me)
- Logging in takes a while, and then I have to download a PDF, with seven full pages, and trawl through for the result (_spoiler alert_: my overdraft is removed)

### :no_good: 5. Actually give people what they ask for

![fees](/assets/img/natwest/natwest_five_unauth_fees.png){:class="img-responsive"}

- I'm told that even if I remove my overdraft I can still go overdrawn - even worse I'll actually get stung with loads of fees :scream:
- I'm removing my overdraft because I want to eliminate the risk of going overdrawn, so ideally I wouldn't be able to go into an 'unarranged overdraft' - why does this have to happen?
- If that's not possible -  I know that sometimes there's still a small chance an offline transaction (e.g. the Tube) might take you overdrawn - let me know why and at least give me a chance (send a notification and give me til the end of the day to add money before applying charges)

### :no_entry: 6. Handle errors elegantly

![overdrafts](/assets/img/natwest/natwest_nine_error.png){:class="img-responsive"}

- 10mins after starting my overdraft journey, my world ends in an unexpected error
- If something fails, let me know why
- If you don't know exactly, give your best guess as to why... is it because it was a Sunday night? Was there maintenance?
- Help me understand when to try again, to avoid me failing repeatedly... should I try again immediately, maybe later today, or should I wait til tomorrow?

<br>

___

<br>

Please help keep us honest and let us know when we fail to meet expectations. We all rely on feedback to improve :relaxed: .

I'm also trying to write better. Let me know how well I'm doing - if you fancy - via email :point_down: .
