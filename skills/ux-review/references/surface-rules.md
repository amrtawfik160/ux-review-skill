# Surface rules

Read each section that matches the surface under review. Examples are invented.

## Forms and unsaved work

For any input, editor or multi-step flow.

**F1. Error, preview and submit share one validity.**
Bad: a time error shows, and Create stays on and saves the previous value. Good: Create stays off until the value is valid.

**F2. Validation accepts what users type.** Try nonsense and each valid format.
Bad: "not a link" passes, or `example.com` fails for lacking `https://`. Good: bare domains pass, and nonsense gets "Enter a website, such as example.com".

**F3. Each option saves what it shows.** Click every option once and do a read-back.
Bad: ticking a second size silently keeps only the first. Good: several sizes save, or the option says "One size per order".

**F4. A disabled submit names what is missing.**
Bad: a grey Save with no hint and an unmarked required field. Good: required fields are marked, and "Add a category to save" sits by the button.

**F5. Every exit guards unsaved work.** Type, then try Cancel, close, back, sidebar links and tab close.
Bad: Cancel erases a long draft in one click. Good: "Discard this draft? Your text will be lost.", with Keep editing.

**F6. The guard fires only when input is at risk.** Leave an untouched form, and leave right after a save.
Bad: "Discard changes?" fires after a successful save. Good: both leave with no prompt.

**F7. Input survives layout changes.** Resize panels and rotate the device.
Bad: resizing a panel clears a typed message. Good: the draft stays.

## Destructive and irreversible actions

For delete, archive, reset or overwrite.

**D1. The confirmation names the item and the result.** It is an in-app dialog with focus off the destructive button.
Bad: "Are you sure?". Good: "Delete 'Q3 plan'? This can't be undone."

**D2. The confirmation names what else goes.** Check linked files, share links, history and shared users.
Bad: deleting a chat silently breaks a link someone was sent. Good: "2 shared links will stop working."

**D3. Undo or archive is offered when possible, with a route back.**
Bad: Archive removes the item for good. Good: "Archived. Undo", and an Archived filter restores it.

**D4. The deletion shows everywhere.** Check lists, counts, search and the old direct link.
Bad: the item is gone from the list and still in the total. Good: counts update, and the old link says "This item was deleted" with a way back.

## Sending, automation and approvals

For anything that acts outside the app or without the user watching.

**O1. Outward defaults are opt-in.**
Bad: a new reminder preselects "All connected channels". Good: "Don't send" is selected, or the user must choose.

**O2. The final review names the exact effect.** It shows recipients, the next run with its zone, and any cost.
Bad: "Chat + 1 more". Good: "Sends to #sales and Dana every Monday at 9:00 (New York)".

**O3. Approvals name the exact request.** They show action, target, account, change, recipients and expiry. Approve-once and a lasting permission are separate controls, and the lasting one states its scope.
Bad: Approve, Reject and Always allow with no action named. Good: "Refund $40 to order 1182. Approve once".

**O4. Approval controls come from the pending-request record.** They leave when the request resolves.
Bad: an approval card sits under a reply that needed no approval. Good: the card appears with the request and goes when it is answered.

**O5. People and channels appear by name.**
Bad: `chan_8f3a2…`. Good: "#sales".

## Time, units and money

For dates, schedules, durations, amounts or totals.

**U1. One zone-aware schedule drives every view.** Compare editor, preview, summary, saved value and computed next run.
Bad: the editor says 8:00, and the job runs at 5:00. Good: every view reads the same value.

**U2. Dates follow the user's zone.** Test away from UTC, across a daylight-saving change, at midnight and at month end.
Bad: "today" flips at 3 AM local time, and a report names no zone. Good: dates are local, and scheduled items name their zone.

**U3. Durations read at a glance, and timers stop.**
Bad: "4127:33" or "98215s". Good: "2d 20h", and an abandoned run reads "Stopped".

**U4. Amounts carry their currency.**
Bad: "150" for 100 dollars plus 50 euros. Good: "$100 and €50", in separate totals.

**U5. Totals state what they include.** Check date range, refunds, hidden items and whose money it is.
Bad: a shared team budget inflates a personal balance. Good: the team page holds it, and the personal balance leaves it out.

**U6. Combined ratios come from totals.** Recompute one.
Bad: average cost per order is the mean of each campaign's average. Good: total cost divided by total orders.

**U7. Formats follow the locale.** Check plurals, number separators, date order and right-to-left layout.
Bad: "12/03". Good: "12 Mar".

## Sign-in, permissions and plans

For accounts, roles, paid features or multi-user screens.

**P1. Hidden or disabled power names its reason.** Sign in as the lowest role.
Bad: an approval card with no buttons and no note. Good: "Only owners can approve. Ask Dana."

**P2. Plan limits are shown to the user.** Run every step on the free plan and watch failed requests.
Bad: a paid-only call fails, and the wizard sits still. Good: the step is skipped, or it explains the limit.

**P3. Sessions hold and stay separate.** Close and reopen, then sign out and sign in as another user.
Bad: a signed-in user is asked to set up again, or sees the last user's data. Good: the user returns to where they were, and sign-out clears the data.

**P4. A forbidden link explains itself.**
Bad: a blank page. Good: "You don't have access. Ask the owner", with a way home.

## Lists, search and imports

For tables, libraries, feeds or imported content.

**L1. Compact lists cap and link out.**
Bad: a home section lists 60 folders. Good: five folders and "See all".

**L2. Filters and position survive the round trip.** Open an item and go back.
Bad: back resets the filter and jumps to the top. Good: the same filter and scroll position return.

**L3. Imports report their rejects.** Validate each imported item.
Bad: "40 photos imported" with five dead links among them. Good: "35 imported, 5 rejected. Review."

**L4. A new item stays findable.** Create one while a filter or search is active.
Bad: the new item saves and the filter hides it without a word. Good: the filter clears, or a note says "Saved. Hidden by your filter."

## Long-running and AI-generated work

For background jobs, streaming output or agents.

**W1. Running work shows its stage, offers Stop and survives reload.**
Bad: a spinner with no text, gone after reload. Good: "Step 2 of 4, reading files", with Stop, back after reload.

**W2. Input sent mid-run shows its outcome.**
Bad: the message vanishes. Good: it shows as queued, or it is applied with a note.

**W3. Facts, calculations and suggestions look different.** Each number names its source and period.
Bad: a suggestion sits inside the results table. Good: results show source and date range, and suggestions sit in their own section.

**W4. Conclusions stay within the data.** Read each generated claim against its data.
Bad: "Order more stock" from page views alone. Good: "Sales data is missing, so this can't be judged yet."
