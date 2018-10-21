---
layout: post
title:  "Broken banking - some learnings"
date:   2018-10-10 15:59:18 +0100
categories: general
---

`Some learnings from the time I removed my overdraft on Natwest.`

<br>

## I'm building a bank at Monzo

Full disclaimer, I'm a Product Manager at [Monzo](https://monzo.com/). Monzo's a UK challenger bank that lives on your smartphone.

## Being in control of your money matters

Control matters a lot, particularly when it comes to money, so I'm always on the lookout for where we can improve this aspect of the banking experience.

I don't use my Natwest account as often as I used to, so I thought I'd remove my overdraft:
- For peace of mind
- To avoid accidental charges (this later proved futile)
- To learn some stuff

**Read on for some learnings.**


<br>

___

## Removing an overdraft with Natwest

### :computer: 1. You'll need a computer, 10mins, and perseverance  

![overdrafts](/assets/img/natwest/natwest_three_change.png){:class="img-responsive"}

- I'm set up for mobile banking so I tried there first, unsuccessfully
- I then logged in online and started my quest to remove my overdraft, first by clicking on 'overdrafts'
- I'm taken to a pop up window, where the options are fairly clear, I want to _change an existing overdraft_
- I'm taken to another page, where I click on _remove an overdraft_

Things get a bit funnier now.

### :bomb: 2. You can't actually guarantee you'll avoid charges

![fees](/assets/img/natwest/natwest_five_unauth_fees.png){:class="img-responsive"}

- I'm told that even if I remove my overdraft I can still go overdrawn
- If I go overdrawn without an 'arranged overdraft' I'll actually get stung with loads of fees
- I don't understand why Natwest will let me go overdrawn without an overdraft set up (unless it's an offline transaction, I don't see why this should happen)... nor why there are such large fees

### :black_nib: 3. You'll need to apply for an overdraft again

![overdrafts](/assets/img/natwest/natwest_five_process.png){:class="img-responsive"}

- To remove the overdraft I'm told I need to 'apply for an overdraft again' (I don't want one)
- This will be actioned _as soon as they can_

### :bookmark_tabs: 4. You'll need a third browser window

![overdrafts](/assets/img/natwest/natwest_six_small_popup.png){:class="img-responsive"}

- Continuing on my mission, I now get a third popup window
- This walks me through the process of _'opening an account'_ (reminder - I'm trying to remove an overdraft :information_desk_person:)
- Thumbs up for accessibility though

![overdrafts](/assets/img/natwest/natwest_eight_threesteps.png){:class="img-responsive"}
- I trundle through three pages asking me to confirm info, including my last three addresses (why?)

### :muscle: 5. You'll need resilience (after all that, it returns an error)

![overdrafts](/assets/img/natwest/natwest_nine_error.png){:class="img-responsive"}
- 10mins after starting my journey, my world ends


### :hourglass_flowing_sand: 6. Removing an overdraft isn't instantaneous

- I try again later and it works
- I'm told my request will be actioned soon
- I wonder why it's not instantaneous

### :mailbox_with_no_mail: 7. The confirmation is a bit much

![overdrafts](/assets/img/natwest/natwest_ten_confirmation_letter.png){:class="img-responsive"}

- A day or so later I get an email that invites me to log back in and view the results of my overdraft application (tension is killing me)
- I download a PDF, with seven full pages!
- I check in my app whether the overdraft has been removed (not just yet)
- I check back in a day later and it's done :tada:

<br>

___
## Here's some learnings

### :zap: 1. Make it in-app, and instant

- No one wants to bank on a laptop anymore
- No one wants to wait, if they feel like they shouldn't have to

### :massage: 2. Make it simple, in one place

- If it can't be on mobile try to keep it all in one place if you can - avoid multiple tabs or windows
- Try to avoid any unnecessary steps, is a form really needed to turn off a feature?

### :question: 3. Be specific, or explain why you can't be

- Vague timelines are frustrating, so try to be specific when you can
- If that's not possible, explain why it's the case

### :no_good: 4. Actually give people what they ask for

- I'm removing my overdraft because I want to eliminate the risk of going overdrawn, so ideally I won't be able to go into an 'unarranged overdraft'
- If that's not possible -  I know that sometimes there's still a small chance an offline transaction (e.g. the Tube) might take you overdrawn - let me know why
- Give people a chance, and make it easy for the user - if I've accidentally gone overdrawn, send me a notification and give me a chance to add money before charging

### :no_entry: 5. Handle errors elegantly

- If something fails, let me know why
- If you don't know exactly, give your best guess as to why... is it because it was a Sunday night? Was there maintenance?
- Help me understand when to try again, to avoid me failing repeatedly... should I try again immediately, maybe later today, or should I wait til tomorrow?

<br>

___

<br>

Please help keep us honest and let us know when we fail to meet expectations. We all rely on feedback to improve :relaxed: .

I'm also trying to write better. Let me know how well I'm doing - if you fancy - via email :point_down: .
