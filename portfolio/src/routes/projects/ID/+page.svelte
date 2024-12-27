<script>
    import '@fontsource-variable/source-code-pro';
    import '@fontsource/gugi';

    import gdd from '$lib/assets/projects/ID/ID-GDD.pdf';
    import gif from '$lib/assets/projects/ID/1.gif'

    

</script>

<style>
    .body {
        margin: 0;
        padding: 0;
    }
    
    .header {
        background-image: url('/src/lib/assets/background-2.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-position: 50% 35%;
        text-align: center;
        padding: 40px;
        color: white;
        height: auto;
    }

    .header h1 {
      font-family: 'Gugi', system-ui;        
      font-size: 4vh;
      color: rgb(255, 255, 255);
      padding: 20px;
      margin: 10px auto;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); 
    }

    .header h2 {
      font-family: 'Source Code Pro Variable', monospace;
      font-size: 2vh;
      color: rgb(255, 255, 255);
      padding: 20px;
      margin: 10px auto;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); 
    }

    .content-row {
        padding: 20px;
        background-color: #ffffff;
        color: #ffffff;
        background: rgba(0, 0, 0, 0.6);
        border-radius: 5px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        margin: 10px 10px;
    }

    .pdfcontainer {
        background-color: #f1f1f1;
        border-radius: 10px;
        padding: 20px;
        margin: 10px auto;
        display: flexbox;
        justify-content: center;
        align-items: center;
        height: auto;
    }

    .pdfcontainer iframe {
        border: none;
        width: 100%;
        height: 80vh;
    }

    .content-row h1 {
        font-family: 'Gugi', system-ui;        
        font-size: 3vh;
        color: #ffffff;
        text-align: center;
        margin: 10px auto;
    }

    .content-row p {
        font-family: 'Source Code Pro Variable', monospace;
        font-size: 3vh;
        color: #ffffff;
        line-height: 1.6;
        padding: 20px;
        margin: 10px auto;
        text-align: center;
    }

    .buttons {
        display: flex;
        justify-content: center;
        padding: 20px;
        margin: 20px auto;
    }

    .button {
        padding: 10px 20px;
        font-size: 2vh;
        font-family: 'Exo 2 Variable';
        margin: 0 10px;
        background-color: #111111;
        color: #ffffff;
        border: none;
        border-radius: 5px;
        transition: all 0.3s ease;
        cursor: pointer;
    }

    .button:hover {
        filter: invert(1);
        transform: scale(1.05);
    }

    .content-row img {
        display: block;
        margin: 0 auto;
    }

    .separator {
        content: "";
        display: block;
        height: 2px;
        background-color: rgb(255, 255, 255);
        border-radius: 1px; 
        width: 80%; 
        margin: 20px auto;
    }

    @media (max-width: 768px) {

    .header h1 {
        padding: 10px;
        margin: 15px auto;
    }

    .header h2 {
        padding: 10px;
        margin: 5px auto;
    }


    .pdfcontainer {
        height: 60vh;
    }

    .pdfcontainer iframe {
        width: 100%;
        height: 50vh;
    }
    
    
}
</style>

<div class="body">
<div class="header">
<h1>Infected Depths</h1>
<h2>Jan 2023 - Present | GODOT/C# · Closed Source </h2>
</div>
<div class="content-row">
    <h1>Project overview presentation</h1>
    <p style="text-align: center;"> 
        A work-in-progress game project that utilises the Godot game engine,
        utilises C# and has allowed for development of other skills in aspects related to building software, Such as game design, art assets, sound processing and implementation of 2D shaders written in a language similar to
        GLSL ES 3.0
    </p>
</div>
<div class="content-row">
    <h1>Early development insight</h1>
    <p style="text-align: center;"> 
        With development being on and off the state of the project has gone through many iterations and changes since I first started. As of September 2024 the project has started on a clean state post migration to Godot 4.0. 
    </p>
    <div class="separator"></div>
        <div class="pdfcontainer">
            <iframe src="https://www.youtube.com/embed/Xs_9VT_CFxY" />
        </div>
    <div class="separator"></div>
    <p style="text-align: center;">
        Early artwork and animation pre-engine upgrade and development restart:
    </p>
    <img src="{gif}" />

</div>
<div class="content-row">
    <h1>Game design document</h1>
    <p style="text-align: center;"> 
        In order to give myself scope and direction for the project, a game development document was produced:
    </p>
    <div class="separator"></div>
        <div class="pdfcontainer">
            <iframe src="{gdd}" />
        </div>
</div>
</div>
