# Summarized: [How to Use Vim - Tutorial](https://www.youtube.com/watch?v=g-XsXEsd6xA)

[Also published at my medium blog](https://medium.com/@anyfactor/summarized-how-to-use-vim-tutorial-2ccdc0336832)

## Insert mode

``i`` → Type at the cursor

``esc`` → Escape any mode

``a`` → After the cursor

``I`` → Type at the beginning of the line of the cursor

``A`` → Type at the end of the line of the cursor

``o`` → Type at a new line after the cursor

``O`` → Type at a new line before the cursor
Navigating

``gg`` → Brings the cursor to the beginning of the file

``G`` → Brings the cursor at the end of the file

``$`` → Brings cursor at the end of a line

``0`` → Brings cursor at the start of a line

``{`` → Next space on a paragraph on a upward direction

``}`` → Next space on a paragraph on a downward direction

``w`` → Go to next word (Rightside)

``W`` → Go to next word seperated by a space (Rightside)

``b`` → Go to previous word (Leftside)

``B`` → Go to previous word seperated by a space (Leftside)

## Searching

``f`` → Finds the associated character starting at the right side of the cursor. E.g. fa birngs cursor to the next "a"

``F`` → Finds the associated character starting at the left side of the cursor

``/`` → Finds a word

``n`` → Circles through found word; progresses on right

``N`` → Circles through found word; progresses on left

``#`` → Finds a words similar to word at cursor

``#`` → Again to progress leftwards

``*`` → Finds a words similar to word at cursor

``*`` → Again to progress rightwards

## Editing

``d`` → Delete something, it should be combined with a navigation command

``dw`` → Delete a word at cursor

``d{`` → Delete entire paragraph

``df)`` → Deletes everything up until ), including ).

``dt)`` → Deletes everything up until ), excluding ).

``3dw`` → Deletes 3 words.

``dd`` → Deletes the entire line at cursor

``p`` → Pastes to the right of the cursor

``P`` → Pastes to the left of the cursor

``di`` → Deletes within specific characters combined with.

``dit`` → Deletes content is within the tag at cursor

``di(``→ Deletes content is within the parenthesis at cursor

``dat`` → Deletes the entire tag content

``ci`` → Deletes character then automatically switches to insert mode

``ci'`` → Deletes characters is inside the closest ' automatically switches to insert mode

``cit`` → Deletes whatever is inside the closest tag, then automatically switches to insert mode

Author of the video: Vim Girl, Freecodecamp