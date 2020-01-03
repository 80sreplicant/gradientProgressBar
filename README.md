-Note

If you are going out of your way to not use the <progress> element because you want to customise it like this, then you absolutely need to re-introduce the accessibility that you've removed through using a <div>

<div
    role="progressbar"
    aria-valuemin="0"
    aria-valuemax="100"
    aria-valuenow="70"
    aria-valuetext="Completed 70%."
>
    Completed 70%
</div>

Remember folks - accessible HTML ain't optional! Ya gotta do it! Also it has the benefit of making your HTML more clear, as it describes its purpose and so becomes self-documenting. Woop!
- User pookage
