GPT-MedAnki-Card-Explainer
==========================
A GPT for explaining content in medically focused Anki flashcards

Current stable version available at:
https://chatgpt.com/g/g-CX92RRG5c-medanki-flashcard-explainer-medical-anki-anking

Beta version: https://chatgpt.com/g/g-zQK0uSYrI-medanki-flashcard-explainer-beta


Example Output for Current Version:
-----------------------------------

Question::

    Patients with narcolepsy and significant {{c2::cataplexy}}
    may benefit from pharmacological treatment with
    {{c1::sodium oxybate}} and/or {{c1::pitolisant}}

Example Output:

    Code:

        .. code-block:: html

            <p><b>Question Explanation Summary:</b><br>
            Patients with narcolepsy and significant cataplexy may find pharmacological relief through sodium oxybate and pitolisant. Sodium oxybate helps regulate sleep patterns and reduce cataplexy, while pitolisant enhances wakefulness by blocking histamine-3 receptors, addressing both excessive daytime sleepiness and episodes of cataplexy.</p>

            <p><b>Memory Aid:</b><br>
            Think "Salt and Pep!" where "Salt" (sodium oxybate) helps calm the storm of narcolepsy by night, and "Pep" (pitolisant) perks up the day. This duo keeps both night terrors and day drowsiness at bay in narcolepsy with cataplexy.</p>

            <p><b>Background Explanation:</b><br>
            Narcolepsy, particularly when accompanied by cataplexy, poses challenges in both night and day symptoms. Sodium oxybate, a central nervous system depressant and the sodium salt of gamma-hydroxybutyric acid (GHB), primarily addresses symptoms during sleep, promoting deep sleep stages and reducing the occurrences of cataplexy. Pitolisant, on the other hand, acts as a wakefulness-promoting agent by antagonizing histamine-3 receptors, thus increasing the release of histamine—a natural body chemical involved in regulating wakefulness.</p>

            <p><b>Footer:</b><br>
            <header style="font-size:9; font-style:italic;">
            MedAnki-Card-Explainer - v0.1.3.2 (Beta) - GPT4 2024-05<br>
            ChatGPT can make mistakes. Consider checking important information.
            </header></p>

            <p><b>Joke:</b><br>
            <header style="font-size:9; font-style:italic;">
            How do you organize a party for narcolepsy medications? You make sure it's a wake!
            </header></p>

    Formatted:

        .. raw:: html

            <p><b>Question Explanation Summary:</b><br>
            Patients with narcolepsy and significant cataplexy may find pharmacological relief through sodium oxybate and pitolisant. Sodium oxybate helps regulate sleep patterns and reduce cataplexy, while pitolisant enhances wakefulness by blocking histamine-3 receptors, addressing both excessive daytime sleepiness and episodes of cataplexy.</p>

            <p><b>Memory Aid:</b><br>
            Think "Salt and Pep!" where "Salt" (sodium oxybate) helps calm the storm of narcolepsy by night, and "Pep" (pitolisant) perks up the day. This duo keeps both night terrors and day drowsiness at bay in narcolepsy with cataplexy.</p>

            <p><b>Background Explanation:</b><br>
            Narcolepsy, particularly when accompanied by cataplexy, poses challenges in both night and day symptoms. Sodium oxybate, a central nervous system depressant and the sodium salt of gamma-hydroxybutyric acid (GHB), primarily addresses symptoms during sleep, promoting deep sleep stages and reducing the occurrences of cataplexy. Pitolisant, on the other hand, acts as a wakefulness-promoting agent by antagonizing histamine-3 receptors, thus increasing the release of histamine—a natural body chemical involved in regulating wakefulness.</p>

            <p><b>Footer:</b><br>
            <header style="font-size:9; font-style:italic;">
            MedAnki-Card-Explainer - v0.1.3.2 (Beta) - GPT4 2024-05<br>
            ChatGPT can make mistakes. Consider checking important information.
            </header></p>

            <p><b>Joke:</b><br>
            <header style="font-size:9; font-style:italic;">
            How do you organize a party for narcolepsy medications? You make sure it's a wake!
            </header></p>



Changelog
---------
* v1.3
  * Add example-set file for memory aids
  * Add joke to output


* v1.2
  * Add "warning" section if card answer is thought to be unclear or incorrect
  * Add memory aid
  * Misc Refinements

* v1.1
  * Add disclaimer on the bottom
  * Misc refinements

* v1.0
  * Initial version