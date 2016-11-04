# Openseadragon Voice Control Plug-in

An OpenSeadragon plugin that provides functionality for text recognition and voice commands like zooming, panning and more...

Demo

See index.html included in this repository


Usage:

Include
    <script type="text/javascript" src='Openseadragon-speechtextrecognition/openseadragonSpeechtextRecognition.js'></script>
    <script type="text/javascript" src='Openseadragon-speechtextrecognition/annyang.js'></script>
    <script type="text/javascript" src='Openseadragon-speechtextrecognition/speech.js'></script>

after OpenSeadragon in your html. Then after you create a viewer:

 var viewer.speechtextrecognition({
        showOptions: true, // Default is false
        speechTextLanguage: 'en-En', // Default is en-EN
        voiceControlLanguage: 'en', // Default is en
        showSpeechtextRecognitionControl: true // Default is true
 });

Avaliable languages:

See Languages.md for more details.
