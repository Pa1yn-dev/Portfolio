<script>
    import '@fontsource-variable/source-code-pro';
    import '@fontsource/gugi';

    import presentation from '$lib/assets/projects/laserSafetyCompliance/stfcPresentation.pdf';

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
        height: 475px;
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

    .content-row ul {
        margin-top: 10px;
        padding-left: 20px;
    }

    .content-row li {
        margin-bottom: 10px;
        font-family: 'Source Code Pro Variable', monospace;

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
        .header {
        height: 400px;
    }

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
<h1>MailLobbyer</h1>
<h2>Jul 2023 - Aug 2024 | C#/HTML/CSS/JAVASCRIPT/RAZOR/ASP.NET
    CORE/ELECTRON.NET · GitHub - Open source </h2>
</div>
<div class="content-row">
    <h1>Project overview</h1>
    <p style="text-align: center;"> 
        Built with ASP.NET Core Blazor with an Electron.Net wrapper, MailLobbyer is a CSV-based emailing program with SMTP server integration. 
        Utilises CSV files with lists of contacts (First name, Surname, Email address, Prefix) and provides personalised emails and emailing lists 
        for batch email sending through the SMTP protocol.
    </p>
    <ul>
        <li>
            Demonstrated the ability to work through a Software Development Cycle in accordance with my client’s requirements through constant 
            communication and a UML design document, from the planning stage to the maintenance stage of the life-cycle.
        </li>
        <li>Cross-platform development, can be deployed to operating systems such as Windows, Linux, and MacOS.</li>
        <li>
            Implemented asynchronous programming and error handling to ensure the system is robust and has optimal performance.
        </li>
        <li>
            Utilised inline C# and HTML/CSS through the usage of Razor in ASP.Net Core, ensuring proper implementation of object-oriented programming 
            (OOP) principles, including encapsulation, inheritance, and abstraction.
        </li>
    </ul>
</div>
</div>
