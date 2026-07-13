# Wise Design - Components

This guide covers the components of the Wise Design System.

## Action prompt

An action prompt is a message that requires the user to actively choose between options.

### When to use

Use an action prompt when you want the user to make a choice. They should have at least two options, even if one is just to dismiss the message.



### Types & Usage

There are 5 types of action prompts: error, warning, neutral, success and proposition. Each has a different use case and rules around their implementation.



#### Error

Use an error to let users know when something has gone wrong and needs their attention. 



#### Warning

Use a warning when you need to alert users to potential issues that could impact their experience. 

These messages are preventative — they help users take action to avoid negative outcomes. 



#### Neutral

Use a neutral prompt for everyday tasks that need a response to move forward. These are functional requests, such as asking a user to "Send" or "Decline" a request for money.



#### Success

Use a success prompt to confirm a process is finished and offer the user their next logical action.



#### Proposition

Use a proposition to encourage the user to take an action that might benefit them. 

Only include a proposition when it fits naturally into the user's current context. Consider what screen they're on and what they've recently done. 



### Placement

Outside of Launchpad, place action prompts where they’re most relevant to what the user is doing. 



### Interaction

#### Dismissibility

If the prompt has two buttons (like "Send" and "Decline") don’t include a close button. In these cases, the message will disappear as soon as the user makes their choice.

Include a close button (X) for optional actions, if either button doesn’t allow the user dismiss the prompt.



#### Call to actions (CTAs)

Action prompts always need a button because their purpose is to get a decision from the user. The button should clearly state what will happen next.



### Writing an Action prompt

Every action prompt must give the user enough information to make a confident choice. You should always:

- Be direct: clearly explain the situation and the choice the user needs to make.
- Use specifics: include names, dates, or amounts to help the user act quickly.
- Write in full sentences: use full stops in body copy to make the text easier to read.

It’s important to consider the tone of your message. Sometimes you might be giving the user good news, and sometimes it might be a warning, or bad news. Depending on the scenario, you'll need to adopt a suitable tone of voice.



#### Error

This prompt must explain what went wrong and how to fix it. Clarity is the most important part of an error message.

**Header**

Be specific and put the most important details first, like the amount or the merchant name, so they understand the issue at a glance.

**Body copy**

Use the body copy to give extra details that help the user solve the problem. Explain why the issue happened and what the next step is.

**Call to action**

The CTA should start with a verb that describes the user's next step or the place they’re going. 





#### Warning

A warning prompt must make the risk clear and the next step obvious. Use every part of the prompt to guide the user toward the right action.

**Header**

Use the header to land the most important information. Be specific and front-load key details so the user understands the risk at a glance.

**Body copy**

Use the body copy to explain the risk and how to avoid it. Be direct about what will happen if they don't act.

**Call to action**

The CTA should start with a verb that describes the specific next step. Avoid generic responses like "OK".





#### Neutral

Use a neutral prompt for everyday tasks that need a response to move forward.

Keep the tone factual and straightforward to help the user make an informed decision without feeling pressured or overwhelmed.

**Header**

Neutral prompts don’t need urgency or persuasion, just clarity. Structure it as a short, declarative sentence or phrase that contains the key information. 

**Body copy**

Use 1 or 2 short sentences to give the user the context they need to make a decision. Stick to details that support the main message or outline the user’s options.

**Call to action**

The button should start with a verb that describes exactly what the user is going to do next. 





#### Success

A success prompt is one of the moments where a warmer tone is appropriate, but clarity still comes first.

**Header**

Use the header to confirm exactly what has happened. Keep it short and put the most important details first so the user gets the message at a glance. 

You can use a warmer tone to celebrate good news as long as the message remains clear.

**Body copy**

Use the body copy to give helpful context or explain the next steps. If there are no specific details to add, you can use this space for a brief celebratory note.

**Call to action**

Your CTA should start with a verb and refer to the action the customer is going to do next, or the place in the product you’re taking them. 





#### Proposition

Use a proposition prompt to introduce something new that's relevant to the user. Use every part of the prompt to give the user a reason to act.

**Header**

Headings are your first opportunity to capture the customer's interest and explain the core value of the proposition. Focus on the single most compelling benefit or the key takeaway that encourages them to learn more.

**Body copy**

Use the body copy to explain how the offer helps the user and encourage them to explore further. 
Provide just enough detail to entice them to take the next step. You should:

- Explain the benefit: clearly state how this proposition helps the user.
- Encourage exploration: hint at what they can discover or do by taking the next step.

**Call to action**

Your CTA should start with a verb and refer to the action the customer is going to do next, or the place in the product you’re taking them. 





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://storybook.wise.design/?path=/docs/prompts-actionprompt--docs) |

---

## Avatar

An avatar is a representation of a unique entity — like a person, a business, or an object. It can contain initials, images, icons, or flags.

### Sizes

Supported sizes are 16, 24, 32, 40, 48, 56,  and 72.



#### Avatar sizes

List item supports five different avatar sizes with 48px as the default, other avatars supported include 32px, 40px, 56px and 72px.



### Media

There are 4 media types available for avatar. Image, flag, icon and text.



#### Image

Images are used to represent either a person or a brand by utilising their logo.





#### Flag

Flags are used to represent either a currency or a country. We support all global flags in our libraries.



#### Icon

Icons are used to illustrate information or as an entry point.

Icon avatars come in an interactive and non interactive state, see more information under interaction.





#### Text

Text is used to represent a person or to showcase there are more than 2 items in a collection on a double avatar.

Text avatars come in an interactive and non interactive state, see more information under interaction.

Size 16 avatar does not support the text variant as it doesn’t pass accessibility standards.





### Types

There are 2 different types of avatar with multiple subtypes underneath each.





### Single

There are 3 types of single avatar, standalone, with a badge or with a notifications.



#### Standalone

When you need to make it easier for a user to identify content, like a recipient or currency.



#### With badge

Badges contain additional information to support avatars, such as flags, the Wise logo, images, statuses actions and references.

There are 6 different types of badges you can use.



#### With notification

Notifications are used to indicate to the user that there is a notification behind the avatar that requires their attention. 

These are primarily used for the profile avatar.



### Double

Double avatars are used when you need to display more than one avatar at the same level of hierarchy. 

This can be useful for representing recipient and currency or for currency conversion.



#### Double horizontal

When you don’t need to retain width alignment with other avatars to keep content aligned — for example in action buttons or tables.



#### Double diagonal

Use when you need to retain width alignment with other avatars — for example in navigation options.



### Interaction

Avatar is used as supporting information, and can be interactive depending on the content it’s paired with or the context it’s in.

These rules only apply to the initials and icon variation of avatar.



#### Selected

Avatars have an optional selected state which can be used when you’re selecting from a list of options. For example choosing a spending category or an icon for your Jar. 

Selectable avatars always need to use the interactive background state.



### Accessibility

Never use an avatar in isolation without copy or interaction cues (such as a chevron icon). This is so that they are clearly identifiable, and aid comprehension and interaction.



### Availability 

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/content/AvatarWrapper#AvatarWrapper) |

---

## Bottom sheet

A bottom sheet is a container you can use to display supporting content or a short, supplementary task on mobile experiences.

### When to use





### Best practice





### Interaction

#### Scrolling the content

The height of the bottom sheet automatically adjusts to the content inside it. But if the content is longer than the maximum height that the bottom sheet can expand to, the content will overflow and become scrollable.



#### Dismissing a bottom sheet

Users can dismiss the bottom sheet by:

- tapping or clicking the close button
- taking an action within the bottom sheet content
- dragging or swiping the bottom sheet down





### Placement

A bottom sheet is a type of overlay that appears on top of the main content on the screen. It’s fixed to the bottom of the screen and sits above a dimmer. 

The dimmer is used to focus the users attention on the bottom sheet content so that the user needs to interact with it before they can progress.



#### Width

Bottom sheets fill the full width the screen on mobile devices.

On wider screens, like iPads, the bottom sheet will fill 2/3 of the width of the screen. Alternatively, you can configure the bottom sheet to adapt so that it displays the content within a different component on wider screens, to match the experience on desktop — for example, a popover, drawer, dropdown, or modal.



#### Height

The height of a bottom sheet automatically adjusts to the content it contains.



#### Safe zone

There’s a 64 pixel safe zone at the top of the screen when the bottom sheet is fully expanded. 

It’s there to reassure users that they are still within the original context, and gives them another way to dismiss.



### Accessibility

Screenreader users won’t be able to use the drag down gesture to dismiss the bottom sheet as swipe gestures are already used to operate voice over software. 

Instead, they can use these alternative ways to dismiss the bottom sheet on each platform.



#### Android

Android users can dismiss the bottom sheet by using the native navigation to go back.



#### iOS

On iOS, a close button appears when VoiceOver is switched on, allowing screenreader users to dismiss the bottom sheet.

There's also a standard iOS [VoiceOver gesture](https://support.apple.com/en-gb/guide/iphone/iph3e2e2281/ios) that allows users to dismiss an alert or return to the previous screen. It’s a two-finger scrub, where you move two fingers back and forth three times quickly in a 'Z' shape.



#### Web

The bottom sheet has an invisible close button on web that screenreader users can tab to.



### Content

There’s a lot of flexibility when it comes to writing for bottom sheets as we don’t specify how the content should be displayed. But when designing for mobile experiences, it’s important to be concise.

It’s also good practice to front load the most important information. For example, if you’re using the bottom sheet to display a list of options, make sure the most relevant or important options are at the top.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/overlays/BottomSheet) |

---

## Button

A button lets the user perform an action with a tap or a click.

### When to use





### Types

There are two different types of button that, default and negative, these designed to emphasise the nature of the action.



### Priorities

Priorities set a visual hierarchy amongst the buttons displayed on the screen to help more important buttons to take precedence over others.



#### Primary

The most important action to move forward in a flow, acknowledge and dismiss, or finish a task.

You should always have one primary button per page where relevant, this can contextually change if another action needs to be completed before being able to proceed.



#### Secondary

Use secondary for providing alternatives to the primary action, or when none of your actions are more important than the others.



#### Secondary neutral

Use secondary neutral for less important convenience actions, such as copying information like bank details with a button, controls or for navigation.



### Sizes

There are three different button sizes, small medium and large, each used for different purposes.



#### Large

The large button is used to move users forward in a flow. 

It’s used at full width on mobile and auto-width, adjusting to the content on desktop depending on use case.



#### Medium

The medium button is used for in line content that needs a greater emphasis than small button or that simply needs to be kept in line with other content on the same line — For example in the nav where you have a 40px close or back icon button.

Medium supports icon left and right, and single or double avatars and wraps to the content.



#### Small

The small button is used for smaller in line content such as list items.

Small button supports icon left and right and wraps to the content.



### Accessories

|  | Media left | Icon right |
| --- | --- | --- |
| __Large__ |  |  |
| __Medium__ | Icon or avatar |  |
| __Small__ | Icon only |  |

#### Icons





#### Avatars





### Interaction

Unless the button is disabled, the user can tap or click on it to perform the action assigned to it.



### Placement

The button should always be contextual, which is why it should be used in line with the content. This gives a stronger cohesion between the context and the action that it performs.

On mobile, if an action must be taken by the user, for example, to finalise something or proceed in the current process, it is best to keep the button visible all the time. 

You can do this by pinning it to the bottom of the screen, outside of the scrolling area. Please pin only one primary action per screen.



### Accessibility

When using buttons on mobile, remember that their height may change based on the user's system-wide preferred font size for accessibility.

For screen reader users, the button's title is read aloud. This emphasises the importance of contextual titles, ensuring all users understand the button's action.

Keep button copy concise. Longer text is harder to scan and increases cognitive load. Also, consider that text length may double when translated.

To ensure users always know what will happen when they interact with a button, the text must be fully visible in all supported font sizes and languages. We don't truncate button text; instead, we allow it to wrap, and the button area grows accordingly.

On small devices, buttons with more than a few words can dominate the screen, reducing the usability of other elements—especially if the button is pinned to the bottom.



#### Disabled states

Consider providing alternative cues explaining why a button is disabled, ensuring screen readers can convey this information, or rethink the design so that buttons are always enabled but provide feedback on required steps before proceeding (e.g. form validation).



### Content

#### Neutral

Use a neutral banner to provide a non-urgent update about the overall account state — for example, when an account has moved from suspended to in-review.

Keep the tone calm and factual to reassure the user without creating unnecessary concern.

**Header**

Neutral banners don't need urgency or persuasion, just clarity. Structure it as a short, declarative sentence that tells the user the current state of things.

**Body copy**

Use 1 or 2 short sentences to set expectations. Tell the user what's happening and whether they need to do anything.

**Call to action**

If a CTA is needed, the button should start with a verb and describe exactly what the user will do or see next. In many neutral cases, a CTA may not be required.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/Button) |

---

## Card

Card is a container that groups related content.

### Types

There are 2 different types of card — Small and large.



### When to use

The card component is ideal for highlighting content whilst still keeping structure. It is primarily used for promotions or conveying crucial information. 

It's also useful for presenting related details about a specific topic. 





#### Small card

Use to display related information on a single subject.



#### Large card

Large cards are best suited for situations where you need to clearly highlight content, like in the case of promotions. 



### Best practices

Utilise cards for presenting both content and actions related to a specific topic. Ensure that cards are designed for effortless scanning of pertinent and actionable details. 

Arrange elements such as text and images on the cards in a manner that effectively communicates their hierarchy.



### Placement





### Interaction

The card component has optional states based on if the card is clickable or static. As well as buttons and dismiss icons.



### Accessibility

The card component scales in height with scaled text.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Carousel Cards

The carousel cards allow us to display different types of information in a carousel pattern.

### When to use

Our carousel cards are used within our carousel pattern to help showcase steps, customer imagery or reviews. We have 5 cards types:

- Image
- Stepper White
- Stepper Neutral
- Video Testimonial
- Text Testimonial


Card types should never be mixed within the same pattern.



### Accessibility

To ensure maximum accessibility for our users, use plain language in accordance with our tone of voice for an inclusive reading experience. The text should be precise and informative. Ensure that images are accompanied by appropriate alternative text (alt text) for screen readers. An ideal alt text is descriptive and concise to convey the meaning and purpose of the image to users who may not be able to see it.



---

## Checkbox

Checkboxes let users select zero, one, or multiple items from a list.

### When to use





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/Checkbox) |

---

## Chip

Chips allow users to filter content or make a choice from a set of options within a compact area.

### Types of chip

You can use chips in 2 different ways — as choice chips, or as filter chips. 

Choice chips let users choose one chip from a set, whereas filter chips let users add multiple filters.



### Choice chips

Choice chips let users choose a single chip from a set.



#### Interaction

Best practice for choice chips is to have one chip pre-selected by default, like radio buttons. This should be the most desired or most frequently selected chip.

Then, if the user wants to make a different selection, they can tap or click on one of the unselected chips. Selecting a new chip will unselect the original one, so there is never more than one chip selected at once.



### Filter chips

Filter chips let users add filters to content by selecting one or more chips from a set.



#### Interaction

Filter chips are unselected by default. The user can then tap or click on each chip to select as many as they like. Tapping or clicking the clear button will unselect the chip.

When selecting a filter chip, it’s also possible to trigger additional input information in a dropdown or bottom sheet. The item selected would form a new chip at the start of the list, while the original chip that triggered the dropdown or bottom sheet would remain in place.



### Placement

Whether you're using filter chips or choice chips, the chips should be placed in a horizontally scrollable row on the screen. 

They can be shown underneath a search field, and are normally positioned towards the top of the screen or above the content that they filter.



### Best practice





### Accessibility

Chips should stay in the same position when selected, as the movement of reordering the list based on selection would add too much cognitive load for users.

With filter chips, if a new chip is added from a bottom sheet or dropdown, it should appear at the front of the list. But the rest of the order should stay the same.



### Content

#### Text

Chip text should:

- be extremely short (just one word where possible)
- describe a single element — (usually a noun)
- work as part of a coherent set (chips are always displayed alongside other chips)
- be in sentence case
- have no full stop





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/Chips#Chips) |

---

## Circular button

A circular button lets the user perform an action with a tap or a click.

### When to use





### Types

Types are designed to emphasise the nature of the action.



### Priority

Priorities set a visual hierarchy amongst the buttons displayed on the screen to help more important buttons to take precedence over others.

Circular buttons support 2 different priorities that can be combined with 2 different types. 



### Best practice





### Interaction

Unless the button is disabled, the user can tap or click on it to perform the action assigned to it.



### Accessibility

Both the icon and font size can change based on the user’s accessibility preferences. When you put circular buttons in a horizontal layout, make sure to flip them to a vertical layout when a huge font size is preferred by the user, so the content still fits on the screen.

When using a screen reader, the text of the button will be read out loud and the icon will be ignored. Make the title contextual, so people completely relying on the screen reader will also understand what the action is related to.



### Content

#### Neutral

Use a neutral banner to provide a non-urgent update about the overall account state — for example, when an account has moved from suspended to in-review.

Keep the tone calm and factual to reassure the user without creating unnecessary concern.

**Header**

Neutral banners don't need urgency or persuasion, just clarity. Structure it as a short, declarative sentence that tells the user the current state of things.

**Body copy**

Use 1 or 2 short sentences to set expectations. Tell the user what's happening and whether they need to do anything.

**Call to action**

If a CTA is needed, the button should start with a verb and describe exactly what the user will do or see next. In many neutral cases, a CTA may not be required.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/CircularButton) |

---

## Compact date input

A compact date input lets people enter a short date within a form.

### When to use





### Best practice





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter (and not a verb)





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Copy Block

The copy block is used to explain our features, benefits or service offering to our users.

### When to use

Our copy blocks are used with the vast majority of our marketing patterns within the system. They are there to allow us to explain our services, benefits and features to our users, usually paired with a button. The block comes in multiple sizes and with a centred or left aligned layout.





---

## Critical banner

Critical banner is used to inform users on urgent, high-priority issues that may significantly impact, their access, security, or data.

### When to use 

Critical banner are used to deliver messages that affects the overall user's account/experience.





### Types & Usage

There are 3 different types of critical banner — error, warning, and neutral. Each has a different use case and rules around their implementation. Generally:





#### Error

Use an error to let users know when something has gone wrong and needs their immediate attention. 



#### Warning

Use a warning when you need to alert customers to potential issues that could impact the entire state of their account.

These messages are preventative — they help customers take action to avoid negative outcomes. 



#### Neutral

Use a neutral prompt when you want to provide information or give a non-destructible update about the overall account. e.g. Account has moved from a previously suspended to an in-review state.



### Placement

Critical banner should always appear fixed at the very top of each screen, above the screen’s main navigation or header. 





### Interaction

In most cases, the button should take the user to a screen where they can fix the issue.

In situations where there are multiple things the user might need to do (for example, if their account is closing) consider having the button open a modal, so that you can provide the user with more information.

A critical banner is not dismissible — it should remain until the user has addressed the issue.





#### Collapse/Expand

For content flexibility in smaller breakpoints, the critical banner can be expanded and collapsed.  

The expanded version is shown on default as the user gets into Launchpad.



### Accessibility

On mobile, the critical banner's height will increase when users have a larger preferred font size set in their system accessibility settings. 

To ensure the banner remains usable at larger text sizes, keep content concise and direct — refer to the [**Writing section**](#writing-a-critical-banner) below for guidance.



### Writing a critical banner

Every critical banner must communicate the state of the user's account clearly and guide them toward resolution. You should always:


- Be direct: clearly explain what has happened to the account and what the user needs to do.
- Use specifics: include deadlines, account states, or required actions to help the user act quickly.
- Write in full sentences: use full stops in body copy to make the text easier to read.

The tone of a critical banner depends on the situation. An error requires urgency and clarity, a warning needs to convey risk without alarm, and a neutral banner should be calm and factual.



#### Error

An error banner tells the user something has gone wrong with their account and needs their immediate attention. Clarity is the most important part of an error message.

**Header**

Be transparent about the state of the account. Front-load the key information so the user understands the situation at a glance.

**Body copy**

Use the body copy to explain what the user needs to do to resolve the issue. Be direct about the required action and its outcome.

**Call to action**

The CTA should start with a verb that describes the specific task or the place the user needs to go.





#### Warning

A warning banner alerts the user to a potential issue that could impact their account if they don't act. Use every part of the banner to make the risk clear and the next step obvious.

**Header**

Use the header to land the most important information. Include a deadline if there is one, and front-load key details so the user understands the risk at a glance.

**Body copy**

Use the body copy to explain the consequence of not acting. Be direct about what will happen if they miss the deadline.

**Call to action**

The CTA should start with a verb that describes the specific task. Avoid generic labels like "OK".





#### Neutral

Use a neutral banner to provide a non-urgent update about the overall account state — for example, when an account has moved from suspended to in-review.

Keep the tone calm and factual to reassure the user without creating unnecessary concern.

**Header**

Neutral banners don't need urgency or persuasion, just clarity. Structure it as a short, declarative sentence that tells the user the current state of things.

**Body copy**

Use 1 or 2 short sentences to set expectations. Tell the user what's happening and whether they need to do anything.

**Call to action**

If a CTA is needed, the button should start with a verb and describe exactly what the user will do or see next. In many neutral cases, a CTA may not be required.





### Availability

| Platform | Available |
| --- | --- |
| Android |  |
| iOS |  |
| Web |  |

---

## Date input

A date input lets people enter a date within a form.

### When to use





### Best practice





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter (and not a verb)





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/DateInput#DateInput) |

---

## Date picker

Use date picker to let users pick a date from a calendar.

### When to use





### Best practice

- Date picker should open the native picker, like the native calendar.





### Availability 

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Divider

Dividers are used to create stronger hierarchy between contents, sub-section, and sections.

### Types

#### Section

Section dividers are used to separate completely unrelated sections of content. 





#### Sub-section

Sub-section dividers are used to separate related pieces of content that require additional hierarchy. 





#### Content

Content dividers are used to break down a specific piece of content or information. They help to visually separate distinct parts, highlight key figures, or introduce summaries within a single content block.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Dropdown

A dropdown (sometimes called a select) lets users choose a single item from a dropdown list.

### When to use





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation ](https://neptune.wise.design/components/inputs/Select#Select) |

---

## Expressive Money Input

Expressive money input is a currency input used exclusively for money movement flows. 

*This is a contributed component.*

### When to use

Use within money movement flows such as send, receive, convert and add. 





### How to use

#### Balance details

Use balance details on the source target currency in the empty state of the component to indicate availability. 



#### Prompts

Use an error prompt to let the user know why they can’t perform an action.



### Interaction

#### Input

Selecting the input will scale the size of the value, typing beyond the length available will scale the size down to fit.

For source and target inputs, the target should update based on the source where relevant.

The input value colour changes between the empty and filled states.



---

## Icon button

An icon button lets the user perform an action with a tap or a click.

### Sizes

Supported sizes are 16, 24, 32, 40, 48, 56,  and 72.



### Priorities

Priorities set a visual hierarchy amongst the buttons displayed on the screen to help more important buttons to take precedence over others.

Icon buttons support 3 different priorities that can be combined with 3 different types. 



#### Primary

Use primary for the most important action to move forward in a flow, acknowledge and dismiss, or finish a task.



#### Secondary

Use secondary for providing alternatives to the primary action, or when none of your actions are more important than the others.



#### Tertiary

Used for controls and views, such as back button or a currency selection.



#### Minimal

Used for dismissive actions like dismiss, or skip. As well as supplementary controls like copying or viewing tooltips.



### Types

Types are designed to emphasise the nature of the action.



### Best practices

Icon buttons work best if they are recognisable without accompanying copy.



### Icon usage

Different icons are used across different use cases. Here are some of our most common use cases



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web Documentation](https://storybook.wise.design/?path=/docs/actions-iconbutton--docs) |

---

## Image Ratios

We use a range of different image ratios across the editorial patterns.

### Image scale

We use a set of image ratios throughout the editorial patterns to ensure that our product and lifestyle photography is correctly displayed.



### Accessibility

To ensure maximum accessibility for our users, use plain language in accordance with our tone of voice for an inclusive reading experience. The text should be precise and informative. Ensure that images are accompanied by appropriate alternative text (alt text) for screen readers. An ideal alt text is descriptive and concise to convey the meaning and purpose of the image to users who may not be able to see it.



---

## Info prompt

An info prompt is a message that appears in a specific part of the screen. It relates directly to a section or multiple components. 
They help the user stay informed, fix something, or get more out of what they’re doing.

### When to use

Use an info prompt if your message is about one specific part of a screen or the user's current activity. Use them to give more context, confirm success, explain a problem, or highlight a benefit related to what the user is doing.





### Types & Usage

There are 5 types of info prompts — error, warning, neutral, success and proposition. Each has a different use case and rules around their implementation. 



#### Error

Use an error to let users know when something has gone wrong and needs their attention. 



#### Warning

Use a warning when you need to alert users to potential issues that could impact their experience. 
These messages are preventative — they help customers take action to avoid negative outcomes. 



#### Neutral

Use a neutral prompt when you want to guide the user or give additional context. These messages are informative rather than corrective.



#### Success

Use a success prompt to communicate that an action or process was completed successfully. These provide positive reinforcement and closure for the user, especially when there's no dedicated success screen. 

This prompt's main job is to confirm success, but it can also guide the user to the next logical step — especially if that helps them benefit from what they just did.



#### Proposition

Use an info proposition to encourage users to learn more about a feature that might benefit them. 

Unlike action prompts which drop users straight into a flow to start a task, info propositions lead to an educational page where they can read the details first.

Only surface a proposition if it’s relevant to what the user is doing. If we show too many, or they feel off-topic, we risk undermining trust and the experience feeling like spam.



### Placement

Info prompts relate to what the user is doing in the moment, so place them next to the section where they’re the most relevant.  



### Interaction

Users can dismiss specific info prompts and  interact with those that include a link.



#### Dismissibility

Users can only dismiss an info prompt if it’s a success, neutral or proposition. 

Errors and warnings provide more urgent information — removing them could lead to a negative outcome for the user. 



#### Links

Only add links if users need extra information to finish their task. Most info prompts should provide enough context so users can stay focused on what they’re doing.

If the prompt includes an action link, it makes the whole component tappable on Android and iOS, as well as mobile web touchscreen devices. 

On web, the link is also clickable and underlined, so it works for click-based interactions too — like using a mouse or keyboard.





### Writing an info prompt

All info prompts should:

- Be clear — explain what’s happened and what to do.
- Be concise — try and use no more than 1-2 short sentences.
- Include key details — if relevant, specify dates, amounts, or names to make the message actionable.
- Use full sentences — write in complete sentences with full stops.


**Headings**

These prompts can include headings when they help users scan and understand content faster. Keep them short and clear so they support rather than compete with your main message.

**Tone**

Vary your tone depending on the type of message you’re giving. Sometimes you might be communicating good news, and sometimes it might be a warning, or bad news. Depending on the scenario, you'll need to use a suitable tone of voice.



#### Error

With any error message, clarity is key. Something has gone wrong and so the job of the prompt is to communicate what’s happened, and how it can be resolved.





#### Warning

We’re highlighting something that could negatively impact the customer’s experience.

It’s important we communicate the issue clearly, explain why it matters and how to avoid any negative consequences. 





#### Success

You’re communicating good news, so don’t be afraid to add energy and colour to the copy. But as with other info prompts, keep this concise — quick positive reinforcement rather than lengthy congratulations. 





#### Neutral

Keep the tone factual and straightforward. 

Focus on providing clear, relevant information that helps the customer understand their situation or options, without overwhelming them with unnecessary details.





#### Propositions 

These messages should feel like helpful suggestions. The goal is to surface value clearly, without coming across as pushy or overwhelming. 

Make sure the message is relevant to what the user is doing and easy to scan.

A more playful or friendly tone can help grab attention and communicate value. But make sure  that tone doesn’t come at the expense of clarity.

Above all else, you want the user to be able to understand the benefit to them without having to guess.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://storybook.wise.design/?path=/docs/prompts-infoprompt--docs) |

---

## Inline Prompt

Inline prompts appear alongside a specific component on the screen. They help the user stay informed, fix something, or get more out of what they’re doing.

### When to use





### Types & Usage

There are 5 different types of inline prompts — error, warning, neutral, success and proposition. Each has a different use case and rules around their implementation. 



#### Error

Use an error to let users know when something has gone wrong and needs their attention. 



#### Warning

Use a warning when you need to alert users to potential issues that could impact their experience. 
These messages are preventative — they help users take action to avoid negative outcomes. 



#### Neutral

Use a neutral prompt when you need to guide the user or give additional context.

Neutral prompts can transition to a success or error message when used in a form.



#### Success

Use a success prompt to communicate that an action or process was completed successfully. These provide positive reinforcement and closure for the user.

You can use a status icon alongside the message — just make sure to use one relevant to the message.



#### Proposition

Use a proposition to encourage the user to take an action that might benefit them. 

These should only appear in list items. The feature or benefit should be clearly related to the action in the list.

Only include a proposition if it’s relevant to what the user is already doing. If we show too many of these prompts, or they feel off-topic, we risk undermining trust and the experience feeling like spam.



### Placement

Inline prompts should appear next to the component they relate to. This helps users connect the message to a specific action.



### Muted

For components that are disabled, the inline prompt will be muted, and displayed with a backslash circle icon where the prompt icon was previously.



### Interaction

#### Links

Avoid adding a link to an inline prompt. These messages should help users complete their current task, not take them to another screen unless absolutely necessary.

Inline propositions should never include a link. This is because they’re designed to supplement an action in a list item with an offer or benefit. 



#### Real-time checks

Inline prompts are also used when forms need to check something in the background, like verifying an account number is real. 

We’ll show a loading message and icon while waiting for the check to finish.





### Writing an inline prompt

All inline prompts should:


- Be specific – clearly starting what the customer needs to know or do.
- Be concise – no more than 2 short sentences so users can quickly understand the message.
- Include key details – use dates, names, or amounts when they add clarity.
- Avoid headings or paragraph breaks – these messages should feel part of the experience, not separate from it.
- Use full sentences with full stops – this helps keep the message clear and professional.

**
Tone**

Your tone should vary depending on the type of message you’re giving. Sometimes you might be telling the user good news, and sometimes it might be a warning, or bad news. Use a tone of voice that matches the scenario. 



#### Error

With any error message, be clear. Something has gone wrong and so the job of the prompt is to communicate what’s happened and how it can be resolved.





#### Warning

Warnings help the user prevent future issues. They need to be clear and concise. 

Use an impartial tone and try to distill your warning down to two parts:


- Explain the potential issue – start by telling the user what could go wrong.
- Give clear guidance – explain what the user can do to avoid a negative outcome.





#### Success

Although you're delivering good news, keep your message concise. This prompt only relates to one component, so avoid an over the top celebratory tone.





#### Neutral

Keep the tone factual and straightforward. Focus on providing clear, relevant information that helps the user understand their situation or options. We don’t want to overwhelm them with unnecessary detail.





#### Proposition

These messages should feel like helpful suggestions. Keep them short, relevant to what the customer is doing, and easy to scan.  

Use a warm, inviting tone but don’t overdo it. The benefit to the user should be obvious and immediate. Avoid wordplay or anything that sounds like a hard sales push. 

If the feature is genuinely helpful, including the benefit in plain English will do the work for you.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | Web documentation |

---

## Instruction

Instructions are a list of bullet points marked as positive and negative.

### When to use





### Best practice





### Content

- Keep each point to a single line.
- Use as few words as possible.
- Points should be statements, not questions.
- All points in a list should relate to one another, and follow the same format.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/content/InstructionsList#InstructionsList) |

---

## List Item - Button

Button item is used when an action is triggered by the list item.

### Usage

List items with buttons can be fully or partially interactive. Buttons should be used to trigger n action — for example ‘change/add’ being the action on a payment method list item.

The secondary priority is the default for list item but can be changed to tertiary or primary depending on your use case. Refer to [button guidance](https://wise.design/components/button).





### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item - Checkbox

Checkbox item allows users to select multiple items from a mutually exclusive list of options.

### Usage





### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item - Icon Button

Icon button item is used to emphasise the action or as a secondary isolated action on the item.

### Usage

If the action is separate from the main list item, the button can be partially interactive. For example when it's being used:

- to copy or edit information
- to link to more detailed additional information
- as a visual aid for a supporting action to the information presented.





### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item - Navigation

Navigation item gives users a rich way to choose between options and navigate to another screen or step in a flow.

### Usage





### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item - No Action

A list item with no action is for information items with no action.

### Usage

When no accessory is used, the full list item is not interactive and **should not provide an action**. 

In-line links can be used within non interactive list items and should be targeted actions with the click/tap area specific to the link itself and not the list item as a whole. See the interaction section below for more info.



### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item - Radio

Radio item allows users to select a single item from a mutually exclusive list of options.

### Usage





### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item - Switch

Switch item allows user to instantly toggle a feature on or off. For example when giving access to receiving notifications.

### Usage





### Availability

| Platform | Availability |  |
| --- | --- | --- |
| Figma |  |  |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## List Item

List items let users review or select options from a dynamic list, adaptable to different use cases.

### When to use

Use a list item when you want to display different options grouped as a list.



### Types

There's six ways to use a list item — navigation, radio, checkbox, switch, icon button and button. 


When a list item is non-interactive with no accessory, it should only display information.





### Avatar

Avatars are optional and are used as a visual aid to the list item. 

[Refer to the Avatar usage guidance.](https://wise.design/components/avatar)





#### Avatar sizes

List item supports five different avatar sizes with 48px as the default, other avatars supported include 32px, 40px, 56px and 72px.



#### Double avatar

**Do:**

**Don't:**





### Prompt

There are 4 different sentiment types for the inline prompt — neutral, positive, warning and negative. 



#### Single line

When the content is short and succinct, the container adjusts to match the width of the content.



#### Multi-line

When the content has multiple lines the validation will stretch to the full width (minus the Avatar).



#### Links

Prompts only ever support a single link. 

On mobile the full prompt is clickable, whereas on desktop only the link is.

Prompt Link content should be intimately connected to the action of the parent List Item. It should take the user to a nearby and quick loading page, not to a totally different part of the website.



### Spotlight

Interactive list items can alternatively be displayed with a spotlight.



#### Inactive

Use to suggest an action the user hasn't done



#### Active

Use to show an option the user has activated



### Interaction

The list item can be either fully or partially interactive based on the accessory used and the use case. 

**Don't:**





#### Fully interactive

All accessories will make the list item fully interactive by default. 

Interacting anywhere on the list item will trigger both the full components associated state as well as the state of the associated accessory.

Fully interactive list items are supported by hover, active, disabled and focus states.



#### Partially interactive

Icon button and button accessories can also be partially interactive, where the touch area area is targeted on the accessory.

The interaction states of these areas depend on the style of the component or text link. Here's how it works:

- Non-interactive list items without any accessory can include inline links.
- Icon button and button can optionally target specific touch areas.
- If a button or icon button list item includes both inline links and accessories, it must be set to partially interactive.





### Content Hierarchy

List item supports default and inverted title and description to allow for further flexibility in the component. 



#### Default values

Title and description values are supported on the default hierarchy of list item. 

They can be used together or in isolation dependant on your use case. 

Both title and description values support sentiment colours as vwell as strikethrough and bold styles.



#### Inverse values

Only the title value is supported on the inverse hierarchy of list item.



### Content

List item supports title, description, supporting info and values.



#### Title

Title copy should:

- be just a few words
- put the most important words first
- summarise or introduce the content it relates to (imagine the user only reads the title)
- be a statement rather than a question (unless the content is asking the user something)
- be in sentence case (only capitalise the first letter of the first word)
- have no full stop





#### Subtitle

Include a subtitle if you have evidence that users need a little more context in order to understand where the navigation option with navigate them. If you include a subtitle for one option in a set, then include it for all of them.

Subtitle copy should:

- be short — aim for a maximum of 2 sentences and remember that content might expand when translated and look different in a list vs tiles
- be plain text — that means no bold text, links, or other fancy formatting
- include a full stop





#### Additional information

Use additional information to add extra details that help make the information clearer for users. Use additional information only after you’ve used the subtitle.

Additional information copy should:

- be clear — aim for a maximum of 2 lines and remember that content might expand when translated and look different in a list vs tiles
- provide a link where relevant – due to technical accessibility constraints, we can only allow for 1 link and it must be appended to the content.





#### Value(s)

Values (optional), can be displayed when you need to display amounts related to the content.

They can be displayed with text formatting (sentiment colours & strikethrough) to enhance a message.





### Accessibility

Provide clear contextual cues to why a list item is disabled by adding a description.

Provide clear feedback when checkboxes or radios are required but left unchecked, by displaying an error validation. 



#### Disabled states

When using disabled states for list item, the action on the list item should be in it’s disabled state, and an inline prompt should be displayed indicating why it’s not available.

The high contrast ratio allows the user to understand exactly why the list item isn’t selectable.



#### Screen-readers

Depending on the platform and screen reader used, the List Item contents can be read out in a different manner. Some screen readers might treat separate parts of the content (e.g. title or subtitle) as a continuous string of text, so it's important to include punctuation whenever applicable to introduce pause and different enunciation. 

For more complicated List Items, e.g. those with values, it may be more user-friendly to change the order of announcements (e.g. title > value > subtitle). All engineering platforms support custom labelling, so care should be taken to ensure good VO experience.  

Do not duplicate the content - if, for example, your List Item's title says `EUR to USD`, remove accessible labels from the associated flag avatars.



---

## Media Button 

Our media button lets the user pause and stop moving content for more control and enhanced accessibility

### When to use

The media button allows users to pause and stop any content that starts moving automatically and moves for more than 5 seconds.



### Placement

The button should be positioned at the bottom right corner of the media.



---

## Modal

A modal is an overlay that interrupts the user’s task to show an important message, disabling the rest of the screen.

### When to use





### Best practice





### Placement

A modal is a type of overlay that appears on top of the main content on the screen. It’s centred on the screen and sits above a dimmer. 

The dimmer is used to focus the user's attention on the modal content, so that the user needs to interact with it before they can progress.



#### Width and height

Modals have a fixed width of 540px on desktop. The height of a modal automatically adjusts to its contents, until it reaches a maximum height of 800px.



#### Safe zone

There’s a 80 pixel safe zone at the top and bottom of the screen if the modal occupies a big space. This is to reassure users that they are still within the original context, and gives them another way to dismiss.



### Interaction

The height of the modal automatically adjusts to the content inside it. But if the content is longer than the maximum height that the modal can expand to, it will overflow and become scrollable.



### Accessibility

Users can dismiss the modal modal in 3 different ways:

- using the close button
- clicking on the dimmed background
- using the escape key

Despite this, never remove the close button on the top. Users will need to find a clear and visible way to dismiss the modal, and get back to their original context.

Avoid using modals too much. They block the screen, have limited space, and demand more attention and focus from the user.



### Content

You can use modals for many different purposes, so the content within them may vary. But there are some general guidelines you should follow.



#### Title

Title copy should:

- be just a few words
- put the most important words first
- summarise or introduce  the content it relates to (imagine the user only reads the title)
- be a statement rather than a question (unless the content is asking the user something)
- be in sentence case (only capitalise the first letter of the first word)
- have no full stop





#### Main content

You should use the main content of the modal to include any supporting information. Supporting information expands on the purpose of the modal, and helps the user make a decision or understand the situation better. 

For example, it might tell the user about the consequences of the action, explain what might happen next, or inform them whether it's irreversible.

Main content copy should:

- be short and to the point — try to use just a few sentences
- be full sentences, with a full stop at the end of each sentence
- use the same language as the title and the action
- be in order of importance — put the most important information first





#### Actions

If you're using a button for the modal action, the button copy should:

- summarise the purpose of the modal — if the user skips the title and the main content, the button should be enough for them to understand what they are about to do
- describe the action in as few words as possible — ideally one or two
- start with a strong, imperative verb, like 'Pay', 'Send' or 'Log in'
- connect to the rest of the copy in the modal — for example, with a primary button it can be good to use the same verb that's in the title
- avoid using first person pronouns like 'me', 'my' and 'I'
- be in sentence case — only capitalise the first letter of the first word
- have no full stop

If you have two buttons on a modal, be careful that the copy doesn't confuse the user. It should be competely clear what each button does. A user shouldn't have to second guess what the result of their actions will be.

An example would be if the modal is asking the user to confirm a cancellation.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Web |  | [Web documentation](https://neptune.wise.design/components/overlays/Modal#Modal) |

---

## Money input

Money input lets users enter an amount in a currency of their choice or validate a prefilled currency.

### When to use





### Best practice





### Placement

Use the money input contextually within flows where the user is sending or converting money.

On web, currency selector options are displayed in a panel. On mobile web they are displayed in a bottom sheet.

On mobile, currency selector options are displayed inside a full page surface.



### Interaction

The interactive parts of the money input are the text input, icon and the currency selector.

Selecting the text input allows the user to type a value.

Clicking or tapping the currency selector trigger shows the user a list of selectable currency options or actions.

Clicking or tapping on the icon performs additional actions and displays extra non critical information.



### Content

The content around the money input should make it clear to users as to what information they need to enter.

For currencies, write [Currency code] + [Currency name]. For example, ARS Argentine Peso. Or AUD Australian dollar.

Don't use currency symbols, because some symbols (like $) could mean multiple different currencies.



#### Currency names

For currency names:

- capitalise the country name, but not the currency
- keep it singular, and don't add an 's'
- remember to include special characters





#### Option group

Make sure you use relevant option group section titles for popular categories.



#### Input label

Label copy should be accurate and make it clear what will happen.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/MoneyInput#MoneyInput) |

---

## Navigation option

A navigation option gave users a rich way to choose between options and navigate to another screen or step in a flow. Navigation options are presented in a list or as tiles (tiles are web only).

It has been deprecated. Please use [list item](https://wise.design/components/list-item).

### When to use





### Best practice





### Presentation

Navigation options are presented in a list or as tiles.



#### List

List presentation shows the navigation options stacked vertically on top of one another. This is well suited to small screen widths, or if you have more than 4 options.



#### Tiles (web only)

Tile presentation shows the navigation options arranged horizontally on the screen. This is well suited to large screens, where you have 4 options or less.

Because the tiles will not wrap on to new lines, they will be forced to display as a list at small screen widths.

With tiles, you can use different media for a single navigation option — one to be displayed when the option is presented as a tile, and one when it's presented in a list.

Tiles can also be rendered at 2 sizes: medium and small.



### Interaction

When a user selects a navigation option, it should navigate them straight to a new screen or step in a flow.

The whole component should be tappable on mobile, and clickable on web.

Navigation options can be disabled, in which case the user will not be able to select them.





### Accessibility

On web, the available area for displaying the media changes between the list and tile views. Make sure the media works at both the small and medium sizes, or provide one for each.



### Content

#### Title

Title copy should:

- be just a few words
- put the most important words first
- summarise or introduce  the content it relates to (imagine the user only reads the title)
- be a statement rather than a question (unless the content is asking the user something)
- be in sentence case (only capitalise the first letter of the first word)
- have no full stop





#### Description (optional)

Include a description if you have evidence that users need a little more context in order to understand where the navigation option with navigate them. If you include a description for one option in a set, then include it for all of them.

Description copy should:

- be short — aim for a maximum of 2 sentences and remember that content might expand when translated and look different in a list vs tiles
- be plain text — that means no bold text, links, or other fancy formatting
- use sentence case — only capitalise the first letter of the first word
- include a full stop





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Web |  | [Web documentation](https://neptune.wise.design/components/options/NavigationOption#NavigationOption) |

---

## Nudge

A nudge directs users to take an action on something that might be relevant at the time they see it.

### When to use





### Variants

There are 7 different variants of nudge, each with a different illustration.



### Placement

Place a nudge at the top of the screen or section it applies to, or below a section header.

Never have more than one nudge on the same screen.



### Interaction

Nudges direct users to another view to complete an action.

Tapping anywhere on the nudge triggers the action — except for the area around the close button, which dismisses it.



### Content

Nudges are for suggesting new features or actions, not for communicating negative or critical information. So while nudge copy should be short and sweet, it's ok to add some energy and colour. Try to have maximum impact, with the minimum amount of words. 

See our [tone of voice](https://wise.design/foundations/tone-of-voice).



#### Title

Title copy should:

- start with a verb
- describe the action the user might like to take
- include a clear benefit for the user — like making something quicker, safer, or cheaper for them
- be short (4–7 words)
- capitalise the first letter of the first word
- not have a full stop

If you can't fit the action and the benefit in one sentence, you can include a second sentence. Just make sure it:

- explains the benefit to the user
- includes full stops as there are 2 sentences
- is short — no more than 6 words





#### Action

Action copy should:

- start with a verb — like ‘add’, ‘enable’, ‘find’
- describe a specific action the user will take — it shouldn't be vague
- be no more than 3 words
- capitalise the first letter of the first word
- have no full stop





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://storybook.wise.design/?path=/docs/prompts-nudge--docs) |

---

## Password input

Lets users enter their password as part of a login or authentication process.

### When to use





### Best practice





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter (and not a verb)





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





#### Placeholders

Placeholders are not supported in most of our components, since (according to our research):

- people may confuse the content with real values
- lack of contrast make them usually difficult to read
- they are often used with dummy values, so aren’t helpful to our users

The optional description offers a good alternative when you need to provide help on how to fill an input.




### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Popover

A popover is a short, floating message that gives the user some non-critical, extra context.

### When to use





### Best practice





### Placement

Only use popovers on web. On mobile and mobile web, show the content in a bottom sheet instead.

Popovers can sit above, below, to the left, or to the right of the button that triggers them.

The component will adjust its placement automatically depending on its position and the space available on the screen.



### Interaction

A popover should always be triggered by a button. The popover appears when the user taps or clicks on the button. It doesn’t appear on hover.

Once a popover has been triggered, it will stay open until the user dismisses it, which they can do by clicking anywhere outside of it.

You can include links in the content, but no other interactive elements.



### Accessibility

Add an aria-label to the icon button that triggers the popover, to hint at the content for those using screen readers.

You can include an image within the content as an extra visual cue, but you should never rely on the image alone to give the user an explanation.

If you include an image, it must be:

- an illustration that has no text within it
- accompanied by a description or some instruction text that's not part of the image





### Content

#### Content

Content copy should:

- define a term or phrase, or give some extra context
- only communicate non-critical information that not every user needs
- be concise — 100 characters or fewer is ideal, but try not to go over 250
- be mostly plain text, but can include links, bold, bullets, and images
- not include any other text styles or interactive elements





#### Title (optional)

Don’t include a title unless you are using the popover to define a term or phrase.

Title copy should:

- be the same as the term or phrase you’re defining
- be sentence case, unless the term has its own capitalisation rules — for example, Direct Debit always has a capital D for Debit because it’s a scheme name
- have no full stop





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Web |  | [Web documentation](https://neptune.wise.design/components/alerts/Popover#Popover) |

---

## Progress Bar 

The Progress bar informs the user that the system needs time to load content. If you are on web please refer to [screen loader guidance page](https://wise.design/components/screen-loader).

### Types

There are two types of progress bars, indeterminate and determinate. 



### When to use

Progress bars are used when the server cannot reliably predict what content will be loaded next.  



### Progress Spinner vs Bar

The progress spinner and bar are used to communicate different loading behaviours.





### Placement and Specs

Place a progress bar within the container that's loading. If a group of items is loading, place a progress indicator at the top of the page, to show progress of the whole group.



### Light and dark mode

Light mode and dark mode use different tapestry fills. 



---

## Progress Spinner

Progress spinner provides reassurance to users that the app hasn’t crashed when they are executing lengthy and/or stressful tasks.

### When to use





### Progress Spinner vs  Progress bar

### Best Practice

Below are a few examples of best practices to consider when using the progress spinner. 



### Content

The spinner and content is always displayed immediately and cycles indefinitely until screen has loaded. The content cycles between four different lines of messaging. The first line of messaging can be changed to give context and explain why the user needs to wait. 




### Placement 

The spinning progress indicator should be centred horizontally and vertically within containers on mobile and web. Test the whole flow to check the screen loaders are consistent in terms of screen location and size. This will help to ensure that spinners that occur one after the other on different screens have the same size and position. 




---

## Promo card

A promo card is used to promote products and features.

### When to use





### Best practices

Content and actions should be related to a specific topic.  

Content such as text and images on the cards should be used to communicate their hierarchy effectively.


Ensure content is scannable and non-obtrusive.



### Placement





### Interaction

The whole card can be clickable, as well as links and buttons.



### Accessibility

The card component scales in height with dynamic text.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Storybook](https://storybook.wise.design/?path=/docs/layouts-promocard--docs "Storybook promo card") |

---

## Radio

A radio lets users select a single item from a mutually exclusive list.

### When to use





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Web |  | [Web documentation](https://neptune.wise.design/components/internal/Radio#Radio) |

---

## Screen loader

A screen loader is a temporary indicator to tell the user that a screen is loading. Once it’s finished, the loader is replaced by the screen. If on mobile please refer to the progress bar guidance page.

### When to use





### Best practice

Make sure screen loaders that show one after the other on different screens are the same size and position. Test the whole flow to check the screen loaders are consistent from start to finish in terms of screen location and size.



### Placement

The screen loader should be centred horizontally on the screen, and be towards the top of the screen on Web. 



### Availability 

| Platform |  | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Search input

A search input allows users to look for information from a wide set of possible results.

### When to use





### Best practice





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter (and not a verb)





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





#### Placeholder

Placeholder copy should:

- be relevant and short
- tell the user what to enter (for example, 'Search')





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Section header

A section header divides sections of a screen.

### Types

There are two different types of section header — section and group.



### When to use





### Best practice





### Content

#### Text

Text should:

- be no more than 3 words
- use a noun that describes the information within the section, like ‘Account services’
- not start with a verb or be an instruction (like ‘Select’ or ‘Choose')





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/content/Section#Section) |

---

## Segmented control

A segmented control allows users to update views of content and select between 2-3 alike options.

### When to use





### Best practice

### Placement





### Interaction

Clicking an alternate option within segmented control slides the active state to the selected option.

Selecting certain options inside forms may trigger alerts.



### Accessibility

For longer translations or scaled content, text will wrap over 2 lines if needed.

Never use truncation, this hides options and is poor for discoverability. 



### Content

Segmented control should be used for assisting users when viewing or updating content, as well as selecting different options within forms. So the copy should always be titled and remain similar to each option.

Options should:

- Be at the top of the hierarchy for the section
- Be short (1–3 words)
- Capitalise the first letter of the first word
- Not have any punctuation







### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Select

A select lets a user pick an option from a long list of options — typically 6 or more.

### When to use





### Placement

- Select is typically used alongside other fields, like in a form.
- On larger screens, you can display multiple fields side by side, but on mobile you should only have one per row.





### Interaction

- Users can use a keyboard to tab through and open a select.
- The select can open different things depending on the platform, such as a dropdown.





### Accessibility

- Select supports TalkBack on Android, and VoiceOver on iOS.





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter, not an instruction





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Snackbar

A snackbar is a brief, temporary notification that confirms the outcome of an action or process that’s just happened.

### When to use





### Best practice





### Placement

Place the snackbar at the bottom centre of the screen. On mobile, make sure it sits just above the bottom navigation.

Only use one snackbar on a screen at once.



### Interaction

Snackbars are temporary, and fade out automatically. The user doesn’t need to interact with them or dismiss them.

The only part of a snackbar that is clickable is the optional button. But don’t include a button unless you really have to. They’re rarely needed.

There should never be more than one button on a snackbar. And the user should still be able to perform the same action somewhere else on the screen.



### Accessibility

Don’t trigger snackbars too often — frequent interruptions are disruptive for people with cognitive and visual impairments.





### Content

#### Text

The text should:

- confirm what just happened
- use the pattern noun + verb
- be 3 words or less
- have no full stop





#### Neutral

Use a neutral banner to provide a non-urgent update about the overall account state — for example, when an account has moved from suspended to in-review.

Keep the tone calm and factual to reassure the user without creating unnecessary concern.

**Header**

Neutral banners don't need urgency or persuasion, just clarity. Structure it as a short, declarative sentence that tells the user the current state of things.

**Body copy**

Use 1 or 2 short sentences to set expectations. Tell the user what's happening and whether they need to do anything.

**Call to action**

If a CTA is needed, the button should start with a verb and describe exactly what the user will do or see next. In many neutral cases, a CTA may not be required.





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/alerts/Snackbar#Snackbar) |

---

## Summary

A summary summarises instructions, tasks, or benefits in a list.

### When to use





### Types

Adding a status is optional. There are 3 status types you can add.



| Type | Icon | Usage |
| --- | --- | --- |
| Done |  | Use this to indicate that a task is complete. |
| Pending |  | Use this to indicate that a task is in progress. |
| Not done | No icon | If an item is not done, it's indicated by the lack of an icon. The content should already clearly communicate what the user needs to do. <br><br>To help those using screenreaders, you can add a ‘not done’ aria label. |

### Best practice





### Interaction

The only interactive parts of the summary are the info button and the action.






#### Info button

Clicking or tapping the info button shows the user some additional information or educational content.

On web, this triggers either a popover or a modal. Use popovers for short definitions or brief bits of additional info, and modals for richer content.

On mobile, interacting with the info button should open a bottom sheet or a full screen modal.



#### Action

The action lets users navigate to a secondary task.



### Accessibility

Be mindful of how frequently you use the info button — too many info buttons add visual noise to the screen, increasing the cognitive load.

You can use an optional status to indicate the state of items that require action — this will add an appropriate aria label for screenreader users, and for some statuses, an icon.

If you do choose to use a status, don't rely on the aria label or icon alone to communicate it. Make sure this information is clear from the title, too. For example:

- 'Verify your address' would match a not done status
- 'We’re verifying your address' would match a pending status
- 'Your address is verified' would match a done status

Statuses are optional as not all summary items are actionable — but if you use a status for one item, you should use a status for all items.





### Content

#### Title

Title copy should:

- sum up a single piece of information the user needs to know
- make the status obvious (if there is one)
- be short — aim for 6 words or less
- use sentence case
- have no full stop





#### Description (optional)

Description copy should:

- expand on the title by providing important, related information
- be plain text — that means no bold, links, or other fancy formatting
- be short — aim for 2 lines and remember content might expand when translated
- use sentence case
- include a full stop





#### Action (optional)

Action copy should:

- direct users to an optional, but directly-related secondary task
- start with a verb
- be 1-3 words
- use sentence case
- have no full stop





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/content/Summary#Summary) |

---

## Switch

A switch lets the user toggle an individual setting on or off.

### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/Switch#Switch) |

---

## Table

Tables allow users to review large amounts of sequential information at a glance.

### Best practices

Tables are useful for organising data in grids and can be used to: Compare data points, Find insights, Find specific information within a large data set, and Show long lists of sequential or structured content. 





### When to use

Use tables when you need to display comparison information across columns and rows.





### Interaction

Users can perform a single action across a row.



### Device

The table component is a mobile responsive web component — at smaller screen widths it activates a horizontal scroll, so that the user can still scan all information.



### Cell types

Table has 5 different cell types used for different types of information — header, leading, text, currency and status.



#### Leading

The leading cell is used for your first table cell to lead the rest of the content. 

While your leading cell should be used as your first cell type, depending on your use case you can use different cell types as your leading cell.

Leading supports default, error and success states.



#### Text

The content cell is used for text based information.

Content supports default, error and success states.



#### Currency

The currency cell is used for displaying currency and currency flags. 

This cell is always right aligned to conform to numerical display standards in tables.

Currency supports default, error and success states.



#### Status

The status cell is used for indicating the status of a row.

Status supports info, pending, warning, error and success states.



#### Header

Table headers are used for identifying the tables primary content.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Tabs

Tabs organise content into sections that users can alternate between.

### When to use





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/content/Tabs#Tabs) |

### Best practice





### Placement

Place tabs at the top of a page or section to categorise content.

Tabs are used for navigating between different available groups of content, it remains at the top of the page so users can see all available content groups.



### Content

Tab labels should describe the content within. They appear in a single row, and are horizontally scrollable if the tab group overflows on the screen.

Options should:

- Be at the top of the hierarchy for the section
- Be short (1–3 words)
- Capitalise the first letter of the first word
- Not have any punctuation





---

## Text area

A text area is a field that lets users enter several lines of text.

### When to use





### Best practice





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter (and not a verb)





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





#### Placeholders

Placeholders are not supported in most of our components, since (according to our research):

- people may confuse the content with real values
- lack of contrast make them usually difficult to read
- they are often used with dummy values, so aren’t helpful to our users

The optional description offers a good alternative when you need to provide help on how to fill an input.




### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  |  |

---

## Text input

A text input lets users enter a single line of text.

### When to use





### Best practice





### Content

#### Label

Label copy should:

- be no more than 3 words
- be a noun that describes the information the user needs to enter (and not a verb)





#### Description (optional)

Description copy should:

- be a single sentence
- give some extra context to help the user enter the right information





#### Placeholders

Placeholders are not supported in most of our components, since (according to our research):

- people may confuse the content with real values
- lack of contrast make them usually difficult to read
- they are often used with dummy values, so aren’t helpful to our users

The optional description offers a good alternative when you need to provide help on how to fill an input.




### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |

---

## Upload input

An upload input lets users upload a single file, or multiple files, within a form.

### When to use





### Types

You can use the upload input to let users upload a single file or multiple files.



### Best practice





### Placement

You can use an upload input on both desktop and mobile screens. Its width should be aligned with the other input fields in a form.



### Interaction

Users can tap or click anywhere on the input field to trigger the upload as the whole area is interactive. This allows them to select the file(s) they want to upload from their device.

Once a file has been successfully uploaded, users can click or tap on the cell to see a preview of the file, allowing them to double check what they uploaded.

Users can also remove a file by pressing the interactive bin icon, at which point we should display a prompt alert to confirm the action. This is a native dialogue alert on iOS and Android, or a modal on web.



### States

The upload input has 4 different states.



### Content

#### Label

The label describes the type of file the user needs to upload, for example 'Invoice'. It should also be consistent with the other labels in the form.



#### Title

In the default state, the title is a call to action. The default copy for this state is 'Upload file' or 'Upload files'. But if you need to change this, treat it like writing button copy. That means starting with a verb, and using as few words as possible.



#### Description

The description describes the state of the upload. For the failed state, it's important to make this copy as specific as possible so the user understands what went wrong and what they can do to fix it.



### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Android |  |  |
| iOS |  |  |
| Web |  | [Web documentation](https://neptune.wise.design/components/inputs/UploadInput#UploadInput) |

---

## Upload

Upload lets users upload a single file when uploading is the primary purpose of the screen.

### When to use





### Best practice

- Include a description if you need to specify the file requirements, such as the type or size (and you haven’t got this info somewhere else on the screen).





### Placement

The upload should be the priority interaction on the screen.



### Interaction

Users can either drag and drop their file, or use the button.



### Content

#### Title

Title copy should:

- be the name of the file the user needs to upload
- be in sentence case
- have no full stop





#### Description (optional)

Description copy should:

- give the user more information about the file requirements
- be 1 or 2 sentences
- have a full stop





### Availability

| Platform | Available | Developer documentation |
| --- | --- | --- |
| Web |  |  |

---

