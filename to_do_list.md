


20240807 
<dataset.py>
study whilst adaption

    My ideas ----

    detect if an image has 'emptiness'. 
    if not so, kick it out, because i need to add distracting scribbles to data.

    For those images with 'emptiness', select its 'irrelevant' match, i.e. the image that bears no shared entities with it; then crop its part to   fill the emptiness. Iteratively, the if the image still has 'emptiness', do it again. Until there is no 'emptiness'.

    The 'irrelevance' needs help from LLM, i believe.

    The caption remains the same.

    Then the dadtaset prep is done.

    The study is aimed to make it known what adatptaion is required to the 'noised' images. Becasue, as matter of fact, the iamges in the vanilla   model is very clean in the measure of category classification, as a great work onf sketch thing.
    In the case of pixel images, it'll be no prob: there are many pixels that is naturally irrelvant.
    but for the sketches in the study, tout est clean. if unclean sketches can do, then canny images can do, too.

    The rebuild should be done to test, train, and val altogether.

    During the process, the 'irrelevant' matches, the posiiton, width, height should be registered.

 I run through the process and adapt it to my problem.


