# coping-recommendation-doc
# penjelasan
dia bakal mengambil mood terbaru sesuai user yang login, lalu dikasih coping recommendation yang sesuai dengan mood nya

endpoint: https://moodify-r25es5rdqq-et.a.run.app/coping/coping-recommendations
- method: GET

- output:
```bash
{
    "message": "Coping recommendations retrieved successfully",
    "recommendations": {
        "text_affirmation_first": "I am resilient in the face of any challenge.",
        "text_affirmation_last": "I deserve love, life, and happiness.",
        "text_instruction": "Box Breathing\r\n\r\nInstruction:\r\n1. Step One: Breathe in through the nose for a count of 4. \r\n2. Step Two: Hold breath for a count of 4. \r\n3. Step Three: Breath out for a count of 4. \r\n4. Step Four: Hold breath for a count of 4. \r\n5. Repeat 3 times",
        "urls": {
            "music": "https://storage.googleapis.com/moodify-bucket-capstone/mood/sadness/music/music_for_sadness.mp3",
            "podcast": "https://storage.googleapis.com/moodify-bucket-capstone/mood/sadness/podcast/podcast_for_sadness.mp3"
        }
    }
}
```


