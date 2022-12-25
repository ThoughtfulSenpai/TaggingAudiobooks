## **Prettify - Clean_underscores_from_fields.**
[open .mta file](https://github.com/ThoughtfulSenpai/TaggingAudiobooks/blob/main/Actions/Audiobooks%23Prettify%23Clean_underscores_from_fields.mta)

When dealing with files that are plagued with underscores:

<img width="917" alt="image" src="https://user-images.githubusercontent.com/100229664/196852459-752c3a89-51c0-47de-9162-69f9ffa87c11.png">

This action will clean them.

<img width="921" alt="image" src="https://user-images.githubusercontent.com/100229664/196852806-7a2e20d9-f446-4a72-8fb1-69d0a76b68c5.png">

## **Prettify - Clean-hyphens-from-fields.**
[open .mta file](https://github.com/ThoughtfulSenpai/TaggingAudiobooks/blob/main/Actions/Audiobooks%23Prettify%23Clean-hyphens-from-fields.mta)

Same as above, but with hyphens. If there is anything worse than metadata with underscores is metadata with hyphens. This action deals with them. _Be careful with this one, though._ Unlike underscores, which have no real use here, sometimes hyphens _may_ have a legit function in names, titles, etc. Use accordingly and watch out for those situations when you **actually** want to keep the hyphens.

## **Prettify - Clean excess whitespaces**
[open .mta file](https://github.com/ThoughtfulSenpai/TaggingAudiobooks/blob/main/Actions/Audiobooks%23Prettify%23%20Clean%20%20%20excess%20%20%20%20whitespaces%20%20.mta)

Normalizes multiple consecutive and redundant whitespaces into just one. Useful when dealing with fields which have multiple whitespaces **anywhere** in the string. Example below: 

![Sin título](https://user-images.githubusercontent.com/100229664/209479284-775d4af4-65e2-40bc-93a3-13fe9211e8f7.png)

The red fields are a mess. They have excess whitespaces before, inside and at the end of the string. The Green field has no excess whitespaces , therefore, it will remain intact. The red ones get normalized. 
Tip. Use this action in conjunction with other prettifying actions for better results.





