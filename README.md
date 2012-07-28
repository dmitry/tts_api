tts_api
=======

Festival and Google TTS API Ruby on Rails service

With this service it's possible to generate synthesized voice in different languages.

For API requests this service uses REST protocol.

/api/sound

Parameters:

text - text (required); it can be in different languages
callback - callback url (optional); it calls page using get request after sound generated with only one parameter `url` (url of sound file)



