GPT-MedAnki-Card-Explainer
==========================
A GPT for explaining content in medically focused Anki flashcards

Current stable version available at: https://chatgpt.com/g/g-CX92RRG5c-medical-anki-flashcard-explainer-anking


Example Output for Current Version:
-----------------------------------

Question::

    Patients with narcolepsy and significant {{c2::cataplexy}} may benefit from pharmacological treatment with {{c1::sodium oxybate}} and/or {{c1::pitolisant}}

Example Output:

    .. code-block:: html

        <p><strong>Question Explanation Summary:</strong><br>
        Patients diagnosed with narcolepsy who also experience significant cataplexy can be effectively managed with pharmacological agents like sodium oxybate and pitolisant. Sodium oxybate helps to consolidate nighttime sleep and reduce cataplexy episodes, while pitolisant, a histamine-3 receptor antagonist, promotes wakefulness and may also help control cataplexy.</p>

        <p><strong>Memory Aid:</strong><br>
        Think "Salt and Pep!" where "Salt" (sodium oxybate) helps calm the storm of narcolepsy by night, and "Pep" (pitolisant) perks up the day. This duo keeps both night terrors and day drowsiness at bay in narcolepsy with cataplexy.</p>

        <p><strong>Background Explanation:</strong><br>
        Narcolepsy is a chronic sleep disorder characterized by overwhelming daytime drowsiness and sudden attacks of sleep. When it occurs with cataplexy (sudden, brief losses of muscle tone triggered by strong emotions), it is known as type 1 narcolepsy. Sodium oxybate, also known as gamma-hydroxybutyrate (GHB), is particularly effective for both sleep disturbances and cataplexy. It acts on GABA-B and GHB receptors, enhancing slow-wave sleep, thus reducing daytime sleepiness and cataplexy frequency.<br>
        Pitolisant, on the other hand, works by blocking the action of histamine-3 receptors, which increases the release of histamine—a wake-promoting neurotransmitter. This not only alleviates excessive daytime sleepiness but has also shown benefits in reducing cataplexy. These medications are critical in the comprehensive management of narcolepsy with cataplexy, targeting both core symptoms of sleep disruption and daytime alertness.</p>

        <header style="font-size: 9pt; font-style: italic;">
        AnKing-Card-Explainer - v0.1.2 - GPT4 2024-05<br>
        ChatGPT can make mistakes. Consider checking important information.
        </header>

    .. raw:: html

        <p><strong>Question Explanation Summary:</strong><br>
        Patients diagnosed with narcolepsy who also experience significant cataplexy can be effectively managed with pharmacological agents like sodium oxybate and pitolisant. Sodium oxybate helps to consolidate nighttime sleep and reduce cataplexy episodes, while pitolisant, a histamine-3 receptor antagonist, promotes wakefulness and may also help control cataplexy.</p>

        <p><strong>Memory Aid:</strong><br>
        Think "Salt and Pep!" where "Salt" (sodium oxybate) helps calm the storm of narcolepsy by night, and "Pep" (pitolisant) perks up the day. This duo keeps both night terrors and day drowsiness at bay in narcolepsy with cataplexy.</p>

        <p><strong>Background Explanation:</strong><br>
        Narcolepsy is a chronic sleep disorder characterized by overwhelming daytime drowsiness and sudden attacks of sleep. When it occurs with cataplexy (sudden, brief losses of muscle tone triggered by strong emotions), it is known as type 1 narcolepsy. Sodium oxybate, also known as gamma-hydroxybutyrate (GHB), is particularly effective for both sleep disturbances and cataplexy. It acts on GABA-B and GHB receptors, enhancing slow-wave sleep, thus reducing daytime sleepiness and cataplexy frequency.<br>
        Pitolisant, on the other hand, works by blocking the action of histamine-3 receptors, which increases the release of histamine—a wake-promoting neurotransmitter. This not only alleviates excessive daytime sleepiness but has also shown benefits in reducing cataplexy. These medications are critical in the comprehensive management of narcolepsy with cataplexy, targeting both core symptoms of sleep disruption and daytime alertness.</p>

        <header style="font-size: 9pt; font-style: italic;">
        AnKing-Card-Explainer - v0.1.2 - GPT4 2024-05<br>
        ChatGPT can make mistakes. Consider checking important information.
        </header>


Changelog
---------
* v1.2
  * Add "warning" section if card answer is thought to be unclear or incorrect
  * Add memory aid
  * Misc Refinements

* v1.1
  * Add disclaimer on the bottom
  * Misc refinements

* v1.0
  * Initial version