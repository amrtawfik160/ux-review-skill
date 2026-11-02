# Core rules

These apply to every screen. Give each rule a verdict. Examples are invented.

## Expectation

**E1. First value comes early.** Move optional questions to after the first success.
Bad: eleven setup screens before the first note saves. Good: the note saves first, and the app asks for a name later.

**E2. Simple by default, deep on request.** Advanced options sit one tap away.
Bad: a sign-up form with twelve fields, nine of them optional. Good: two fields and a "More options" row.

**E3. Every default works today.** Open each preselected value.
Bad: "New message" is addressed to a paused teammate. Good: it preselects an active teammate, or asks.

**E4. Success lands on the result.** After a create or save, show the new item and one next step.
Bad: the item saves, and the user stays on step 3 with a disabled button. Good: the new item opens with "Add your first task".

**E5. New accounts see first-run content.** Read everything a brand-new account sees that is written for returning users.
Bad: a new account gets "120 new features since your last visit". Good: it gets one starter tip.

**E6. A redesign keeps what users relied on.** Compare the old and new inventories from step 1, and name each removal with its reason.
Bad: export disappears because the reference design had none. Good: export moves to the overflow menu, and the report says so.

**E7. A reference is adapted.** Write what fits this product before you use it, and show each piece of content once.
Bad: a copied layout repeats the summary in a header and a side card. Good: the layout idea stays, and the summary appears once.

## Truthful status and copy

**T1. A status word comes from a real check.** Find what sets each badge.
Bad: a green "Connected" on a sync whose first read fails. Good: "Connected, last sync failed. View details".

**T2. Each stage reports its own result.** Fail the last stage of a task and read the outcome.
Bad: a finished report sits under "Failed, try again". Good: "Your report is ready. Saving to history failed. Retry saving."

**T3. Errors name the cause and the next step.** Read each one as someone with no logs.
Bad: "Unavailable". Good: "Can't publish yet. The cover image is missing. Add image."

**T4. A button does what its label says.** Do a read-back after each click.
Bad: "Confirm" moves on and saves nothing. Good: the confirmed item is in the list after reload.

**T5. Copy describes the current configuration.** Change each setting, reread the text around it, and hide empty template slots.
Bad: "Shares results with your team" while set to log only, or "Assigned to: .". Good: "Saves here for review. No message is sent."

**T6. Copy fits the outcome and the count.**
Bad: "Your result will appear soon" on a finished run, a celebration at 20%, or "1 days". Good: "This run finished, but no result was saved", "Try these 8 again", and "1 day".

**T7. Zero, missing and failed look different.** Compare them side by side.
Bad: a missing amount shows as 0.00 and joins the total. Good: "Amount missing" stays out, and the total says "1 item excluded".

**T8. Each label matches its data.** Check one number against its source of record.
Bad: "Unique visitors" is fed by page views. Good: each metric has its own labeled column.

**T9. Promises match the system.** Test or read each stated limit, retention period and guarantee.
Bad: "Backups kept for 90 days" while a weekly job clears them. Good: the copy states the real period.

## Dead ends and recovery

**R1. Every click answers.** Feedback shows within 100 ms, and the click reaches its result or says why it cannot.
Bad: tapping a file in a side panel does nothing. Good: it opens, or says "This file is no longer available".

**R2. Every list and picker offers a way forward.** Check it empty and with no matches.
Bad: an account picker finds nothing and offers nothing. Good: a "Create 'Travel'" row sits under the results.

**R3. Whatever closes can reopen.** Close each panel, menu and sidebar, then find the way back unaided.
Bad: a collapsed sidebar returns only through a faint unlabeled icon. Good: a labeled control sits where the panel was, or the panel stays open.

**R4. Status rows open their subject and its fix.**
Bad: "Sync failed" opens a blank page. Good: "Sync failed. Fix" opens that connection's settings.

**R5. An action clears what prompted it.**
Bad: "Update now" restarts the app into the same prompt. Good: the update applies once, and the prompt ends.

**R6. Every offered option works today.** Follow each entry point to its end.
Bad: "Connect your calendar" as a first choice leads to "Not available yet". Good: the option appears once it works, or reads "Coming soon" before any tap.

**R7. Dismissed suggestions stay dismissed.** Close each promo and tip, then reload.
Bad: an upgrade card returns on every visit. Good: it stays closed for that user.

## Consistency

**C1. One thing has one name.** List each screen's nouns and merge the synonyms.
Bad: "Library" in the sidebar and "Files" on the page. Good: "Files" in both.

**C2. One action behaves the same at every entry point.**
Bad: Delete on a card confirms, and Delete on the detail page only navigates back. Good: both open the same named confirmation.

**C3. A changed pattern changes everywhere.** Find every use of a redesigned component or its content.
Bad: a new card on Home while the full page keeps the old one. Good: both ship together.

**C4. A user choice holds everywhere.** Set each preference, then check dialogs, widgets, exports and notifications.
Bad: the user picks euros, and a dialog shows dollars. Good: euros show everywhere, and a hidden balance stays hidden in the widget.

**C5. Counts match their lists and name what they count.**
Bad: "50 of 980" with no noun, or a badge of 3 over an empty inbox. Good: "Showing the first 50 of 980 orders", and the badge opens its 3 items.

## Accessibility

**A1. Every control has a name in the accessibility tree.**
Bad: a focusable upload button with no name. Good: "Upload a file", with decorative duplicates out of the tab order.

**A2. The keyboard does everything.** Tab order follows the layout with visible focus, Escape closes overlays, and focus returns to the opener.
Bad: focus lands behind an open dialog. Good: focus stays inside until close, then returns to the trigger.

**A3. Contrast is measured on the real background.** Text needs 4.5:1, and large text and icons need 3:1, in every theme and on tinted strips.
Bad: red error text on a pale red strip at 3.1:1. Good: a darker red at 4.8:1.

**A4. Every color cue has a word or shape beside it.** Check in grayscale.
Bad: paid and unpaid differ only by a green or red dot. Good: each dot has a word.

**A5. Async changes reach screen readers.**
Bad: a toast appears in silence. Good: a status region announces "Saved", and each error is linked to its field.

**A6. Content reflows at 200% zoom.**
Bad: a fixed-height dialog hides its submit button. Good: the dialog scrolls and keeps its actions reachable.

## Mobile

**M1. The primary action is visible at 390.** The page scrolls only vertically, and floating elements sit clear of controls.
Bad: a floating badge covers the first Review button. Good: the badge moves clear.

**M2. The on-screen keyboard fits the field.** Focus each field with the keyboard open.
Bad: a digit in an email field flips the keyboard back to letters, or the field hides under it. Good: the email keyboard stays put, and the field scrolls above it.

**M3. Touch targets reach 44x44 and work without hover.**
Bad: a row's Delete appears only on hover. Good: a visible menu button holds Delete.

**M4. Bottom content clears the safe area.** Check the home indicator and the last item of each scroll.
Bad: the Next button touches the screen edge. Good: it clears the safe area with standard spacing.

**M5. Each gesture has one owner.** Scroll inside pagers and sheets, and try the system back gesture.
Bad: scrolling a document sometimes jumps to the previous page. Good: paging starts only from a deliberate horizontal swipe.

## Visual accuracy and motion

**V1. Contents sit centered within 1px.** Measure it in the browser.
Bad: the placeholder sits 3px above the send button's center. Good: icon, text and button share one center line.

**V2. Diagram lines end on their handles, on separate paths.** Labels sit clear of lines.
Bad: Yes and No lines cross under their labels. Good: each branch leaves its own handle.

**V3. Images are sharp at device pixel ratio 2 and 3.**
Bad: a 32px image in a 48px avatar slot. Good: a source three times the display size.

**V4. Layout holds still as data arrives and hover changes.**
Bad: a late banner pushes the list down. Good: the banner has reserved space.

**V5. Motion explains a change.** Each animation shows where something came from or went, runs 150 to 300 ms, can be interrupted, and exits too. Actions done many times a day stay still.
Bad: rows fade in on every tab switch. Good: a sheet rises from its button and returns there.

**V6. Reduced motion is honored.** Turn the setting on and repeat the flow.
Bad: a looping background keeps moving. Good: it holds still, and state changes use a short fade.
