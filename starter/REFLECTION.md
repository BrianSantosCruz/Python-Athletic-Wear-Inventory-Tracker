# Written Reflection


## Assumptions (Question, Assumption, Risk)


1. Assumption 1
   - **Question:** What amount of stock causes a product to be labeled as low?
   - **Assumption:** I will estimate that low stock is around a quantity of 10.
   - **Risk:** If this is wrong, the real low amount will be overlooked, and my code may overlook when a product is low altogether. I would ask the stakeholder and check in comparison with the amount of other similar products.
2. Assumption 2
   - **Question:** What do the empty lines in the datafile mean?
   - **Assumption:** The empty lines in the datafile are simply for spacing, but must be taken into consideration when counting lines.
   - **Risk:** If this is wrong, I can easily miss or format information incorrectly, messing up outputs and results that the manager needs. I would check the outputs and see if the two empty lines are accounted for, and edit code in response.

## The 3+ edge cases you found and handled

> **Instructions (delete before your final push):** for each one, give
> the exact line from your data file, what was wrong with it, and what
> your code does about it. Say whether it skips the line or fixes it. See
> `data/SOURCE.md` for the full list of edge-case types. You need at
> least 3 different types.

1. _TODO_
2. _TODO_
3. _TODO_

## Function scope

> **Instructions (delete before your final push):** in your own words,
> why doesn't a variable created inside one of your functions change a
> variable with the same name somewhere else in the script? What would
> break if every variable were visible everywhere?

_TODO_

## Search complexity: linear scan vs. dict lookup

> **Instructions (delete before your final push):** which data structure
> holds your items (a list, a dict keyed by name, or something else)? How
> does `find_item` look an item up by name? Label your `find_item`'s time
> complexity: O(n) for a linear scan, or O(1) on average for a dict
> lookup. Then explain, using your own code, what happens to
> `find_item`'s runtime if the inventory grows from about 25 items to
> 10,000.

_TODO_

## AI-assisted edge-case discovery

> **Instructions (delete before your final push):** your data file has
> more edge cases than the 3 you need, and real business data has
> problems nobody planted on purpose. In 1-2 sentences each: what prompt
> would you give an AI assistant to help you think of more kinds of bad
> or unexpected input than you found by hand? How would you check its
> suggestions before trusting them? Name a specific check, not "I'd be
> careful."

_TODO_

## One real AI prompt, checked

> **Instructions (delete before your final push):** paste one prompt you
> actually used with an AI during this sprint, word for word, in the box
> below. Then fill in the four lines under it:
>
> - **Technique:** which technique(s) it uses (Task / Context / Evidence /
>   Output, one-shot, XML tags, plan mode, tests and edge cases), and
>   where each one shows up in the prompt.
> - **What came back:** the AI's answer, trimmed but not reworded.
> - **How I checked it:** one concrete check you ran yourself: a case you
>   worked by hand, a test you wrote, or re-running your code on your
>   data file.
> - **What the check showed:** was the answer right, partly right, or
>   wrong? What did you keep, change or throw out?
>
> Didn't use AI? Write the prompt you would have used, label it "not
> sent", and run the same check on your own code instead.

```text
(paste your prompt here)
```

- **Technique:** _TODO_
- **What came back:** _TODO_
- **How I checked it:** _TODO_
- **What the check showed:** _TODO_
