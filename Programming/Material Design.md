# Writing - Material Design

## Principles

UI text can make interfaces more usable and build trust. Text should be clear, accurate, and concise.

**Be concise**

To facilitate navigation and discovery, write UI text in short, scannable segments that focus on a limited number of concepts at a time.

To facilitate navigation and discovery, write UI text in short, scannable segments that focus on a limited number of concepts at a time.

> Send money to anyone in the US who has an email address. It's fast, easy, and free.
> 
> 
> **Do**
> 
> *Express information and actions concisely.*
> 

> Send (and receive) money with friends and family in the US with an email address. It's a two-step process with little latency and there aren't any charges for the recipients. 
**Don't** 
*Don't list many complex implications when introducing a key action or concept.*
> 

> Read the instructions that came with your phone
**Do**
*Write instructions that focus on a small number of key concepts.*
> 

> Consult the documentation that came with your phone for further instructions
**Don't**
*Don't embed instructions within lengthy descriptions.*
> 

---

**Write simply and directly**

Use simple, direct language that makes content easy to understand.

> Save changes?
**Do**
*Keep UI text short.*
> 

> Would you like to save your changes?
**Don't**
*Don't write instructions that are longer than necessary to communicate an action.*
> 

> Register to vote
**Do**
*Write UI text focused on the current task.*
> 

> You must register before you can vote
**Don't**
*Tell the user how to take action, not that they should or must do so.*
> 

---

**Address users clearly**

Address users in either the second person (you or your) or the first person (I, me, or my), depending on which is suitable and clearest for the situation.

Each form of address is recommended for the following contexts:

- **Second person, "you" or "your"**: This conversational style is appropriate in most situations; as though the speaking directly to the user.
- **First person, "I" or "my"**: In some cases, this form of address emphasizes the user's ownership of content or actions.

> Quickly open the camera without unlocking your screen
**Do**
*Speak directly to the user in the second person.*
> 

> I agree to follow the terms of service
**Do**
*Emphasize ownership of actions using the first person.*
> 

> Your places
**Do**
*Speak directly to the user in the second person.*
> 

> My Account
**Do**
*Emphasize content ownership using the first person.*
> 

### Avoid combining first and second person

To avoid confusing the user, avoid using "me" or "my," and "you" or "your," in the same phrase.

Change **your** preferences in **My** Account**Don't**Don't refer to the user in both the second person and the first person within the same phrase.

---

**Communicate essential details**

Communicate only essential details so users can focus on their own tasks. Sometimes the most effective UI contains no text at all.

> **Signing in**...Your phone is contacting us. This can take up to 5 minutes.
**Do**
*Communicate the details that are essential to understanding a current state or action.*
> 

> **Signing in**...Your phone needs to communicate with our servers to sign in to your account. This may take up to 5 minutes.
**Don't**
*Avoid providing details that aren't essential for the user to know, such as how an action or process is performed.*
> 

---

**Write for all reading levels**

Use common words that are clearly and easily understandable across all reading levels.

> Turn on Location History
**Do**
*Use common words.*
> 

> Enable Location History
**Don't**
> 

### Industry terms and feature names

Avoid industry-specific terminology or names invented for UI features.

> Preparing video…
**Do**
*Use common words.*
> 

> Buffering…
**Don't**
*Don't use technical jargon, unless it’s critical to understanding the context.*
> 

> This command isn't supported on your phone
**Do**
*Use common ways of describing both the UI and devices.*
> 

> This command is only supported on dual-core devices
**Don't**
*Don't use technical language to describe, unless it’s necessary to understanding the context.*
> 

---

**Write in the present tense**

Use the present tense to describe product behavior. Avoid using the future tense to describe the way a product always acts.

When you need to write in the past or future tenses, use simple verb forms.

> Message sent
**Do**
*Write in the present tense.*
> 

> Message has been sent
**Don't**
*Don't write in different variations of the present tense, such as the present perfect tense.*
> 

---

**Use numerals**

Use numerals ( "1, 2, 3," not "one, two, three") unless writing copy that mixes uses of numbers, such as "Enter two 3s."

> You have 3 messages
**Do**
*Use numerals.*
> 

> You have three messages
**Don't**
*Don't spell out numbers.*
> 

> Enter two 3s
**Do**
*When using numbers two different ways, refer to one in numerals and the other in text.*
> 

---

**Skip unnecessary punctuation**

To help readers scan text at a glance, avoid using punctuation in places where it isn't necessary.

### Periods

Avoid using periods on solitary sentences within these UI elements:

- Labels
- Hover text
- Bulleted lists
- **[Dialog](https://material.io/design/components/dialogs.html)** body text

Use periods on:

- Multiple sentences
- Any sentence followed by a link (links themselves should not be full sentences)

### Periods in longer text

Longer or complex sentences can use periods if doing so better suits the context. For example, if the rest of your app's flow doesn't use periods, introducing them in a few places may appear inconsistent.

> **Undo bulk edit?** If you undo this bulk edit, everything you changed will go back to its previous state
**Do**
*Skip periods after solo sentences of body text.*
> 

> **Undo bulk edit?** Everything you changed will go back to its previous state.
**Don't**
*If there is only a single sentence, don't place periods after body text.*
> 

### Colons

Skip colons after labels.

> Share with
**Do**
Share with:
**Don't**
> 

---

## Content structure

**Begin with the objective**

When a phrase describes a goal and the action needed to achieve it, start the sentence with the goal.

> To remove a photo from this album, drag it to the trash
**Do**
*Start a statement with the objective (“to remove a photo”) and end it with the user action (“drag it to the trash”).*
> 

> Drag a photo to the trash to remove it from this album
**Don't**
*Don't state the action the user takes (“drag a photo”) before the objective (“to remove it from this album”).*
> 

---

**Reveal detail as needed**

Reveal information progressively and as it's needed.

In a user's first interaction, every detail doesn't need to be described. Reveal more detail about features as the user explores them and needs more information.

> Remove downloaded book?
**Do**
> 

> Are you sure you want to remove this downloaded book? You won't be able to access it unless you're online.
**Don't**
> 

---

**Use consistent words**

Use words in a consistent manner across your UI features.

> **Remove photo**
Remove photo from page?
**Do**
*Refer to an action with consistent language throughout your UI.*
> 

> **Remove photo**
Delete photo?
**Don't**
*Don't describe an action using different verbs across your UI.*
> 

---

**Refer to UI elements and controls by label**

Labels identify what a control or element does. They appear either on or near the control itself, such as the text on a button or switch. To refer to a UI control or element, mention it using its label text. (don't state the type of element or control).

> Click Continue
**Do**
*State the UI element's label only.*
> 

> Click the Continue button
**Don't**
*Don't state both the label and the element on which it appears.*
>