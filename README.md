<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aimbot V3 - README</title>
    <style>
        :root {
            --dark-bg: #0d1117;
            --primary-bg: #161b22;
            --text-color: #c9d1d9;
            --header-color: #ffffff;
            --accent-color: #58a6ff;
            --border-color: #30363d;
            --code-bg: #010409;
            --details-bg: #21262d;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
            line-height: 1.6;
            font-size: 16px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: var(--primary-bg);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 25px 45px;
        }

        h1, h2, h3 {
            color: var(--header-color);
            font-weight: 600;
            margin-top: 1.6em;
            margin-bottom: 0.8em;
            padding-bottom: 0.3em;
            border-bottom: 1px solid var(--border-color);
        }

        h1 {
            text-align: center;
            font-size: 2.2em;
            border-bottom: 2px solid var(--border-color);
            margin-top: 0;
        }
        
        h1 img {
            vertical-align: middle;
            margin-left: 10px;
        }

        h2 {
            font-size: 1.7em;
        }

        h3 {
            font-size: 1.3em;
        }
        
        p {
            margin-bottom: 1em;
        }
        
        a {
            color: var(--accent-color);
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        strong {
            font-weight: 600;
            color: var(--header-color);
        }

        .code-container {
            position: relative;
            margin: 1.2em 0;
        }
        
        pre {
            background-color: var(--code-bg);
            padding: 16px;
            border-radius: 6px;
            border: 1px solid var(--border-color);
            overflow-x: auto;
            white-space: pre-wrap;
            word-wrap: break-word;
            font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, Courier, monospace;
        }
        
        code {
            font-size: 0.9em;
        }

        .copy-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            background-color: #21262d;
            color: #f0f6fc;
            border: 1px solid var(--border-color);
            padding: 5px 10px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 0.85em;
            transition: background-color 0.2s;
        }

        .copy-btn:hover {
            background-color: #30363d;
            border-color: #8b949e;
        }
        
        .copy-btn.copied {
            background-color: #2ea043;
            border-color: #2ea043;
        }

        details {
            border: 1px solid var(--border-color);
            border-radius: 6px;
            margin-bottom: 1em;
            background-color: var(--details-bg);
        }
        
        summary {
            font-weight: 600;
            padding: 12px 16px;
            cursor: pointer;
            outline: none;
        }

        .details-content {
            padding: 0 16px 16px;
            border-top: 1px solid var(--border-color);
        }

        ul {
            list-style: none;
            padding-right: 20px;
        }

        ul li {
            position: relative;
            padding-right: 20px;
            margin-bottom: 8px;
        }

        ul li::before {
            content: '-';
            position: absolute;
            right: 0;
            top: 0;
            color: #8b949e;
        }
        
        .documentation-link a {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 10px 20px;
            border-radius: 6px;
            text-align: center;
            font-weight: bold;
            transition: background-color 0.2s;
        }

        .documentation-link a:hover {
            background-color: #388bfd;
            text-decoration: none;
        }

        video {
            max-width: 100%;
            border-radius: 6px;
            margin-top: 1em;
            border: 1px solid var(--border-color);
        }

        .note {
            padding: 1em;
            background-color: var(--code-bg);
            border-left: 4px solid #f85149;
            border-radius: 4px;
        }

    </style>
</head>
<body>

    <div class="container">
        <h1>☄️ Aimbot V3 
            <a href="https://exunys.gitbook.io/aimbot-v3-documentation" target="_blank">
                <img src="https://visitor-badge.laobi.icu/badge?page_id=Exunys.Aimbot-V3" alt="Visitors">
            </a>
        </h1>

        <p>This project is a universal aim-locking module that works with all games using the default character. This version includes several improvements over <a href="https://github.com/Exunys/Aimbot-V2" target="_blank">Aimbot V2</a>, with key enhancements being optimization and numerous rewritten parts for maximum efficiency.</p>
        <p>The source of this project is optimized, organized, and simplified to the highest level to ensure it is efficient, fast, stable, and precise.</p>
        <p>This project is currently in beta testing. Feel free to create pull requests (you will be credited), report issues, or contact me through any of my linked platforms.</p>
        <p>This module is used in <a href="https://github.com/Exunys/AirHub-V2" target="_blank">AirHub V2</a>. If you want to use it personally instead of integrating it for development purposes, I recommend using AirHub.</p>

        <h3>📜 License</h3>
        <p>This project is completely free and open source. However, that does not mean you own the rights to it. Please read this <a href="https://github.com/Exunys/Aimbot-V3/blob/main/LICENSE" target="_blank">document</a> for more information. You can reuse or integrate this script or any system from this project into your own repositories, as long as you credit the developer, <a href="https://github.com/Exunys" target="_blank">Exunys</a> (me).</p>

        <h3>❗ Notice</h3>
        <p>This project has been written and tested with Synapse X and Electron. However, I will do my best to modularize support for every exploit. So far, the required functions for this module to run are listed below:</p>

        <details>
            <summary>Dependencies (required functions & libraries):</summary>
            <div class="details-content">
                <h4>Libraries:</h4>
                <ul>
                    <li><strong>Drawing</strong>
                        <ul>
                            <li>Drawing.new <em>(function)</em></li>
                            <li>Drawing.Fonts <em>(table)</em></li>
                        </ul>
                    </li>
                    <li><strong>debug</strong>
                        <ul>
                            <li>debug.getupvalue <em>(function)</em></li>
                        </ul>
                    </li>
                    <li><strong>Input</strong>
                        <ul>
                            <li>Input.MouseMove <em>(function)</em> - Alternative to <strong>mousemoverel</strong></li>
                        </ul>
                    </li>
                </ul>
                <h4>Functions:</h4>
                <ul>
                    <li><strong>getgenv</strong></li>
                    <li><strong>getrawmetatable</strong></li>
                    <li><strong>mousemoverel</strong> / <strong>Input.MouseMove</strong></li>
                </ul>
            </div>
        </details>

        <h2>📋 Documentation</h2>
        <p class="documentation-link">
            <a href="https://exunys.gitbook.io/aimbot-v3-documentation/" target="_blank">Click here for full documentation.</a>
        </p>
        <p>More detailed information for this project will be documented by time in this README.md document but mostly on the gitbook page.</p>

        <h2>👋 Introduction</h2>
        <p>First of all, to implement the module in your script's environment you must use the function <code>loadstring</code> like below:</p>
        <div class="code-container">
            <button class="copy-btn" onclick="copyCode(this)">Copy</button>
            <pre><code>local Aimbot = loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V3/main/src/Aimbot.lua"))()
Aimbot.Load()</code></pre>
        </div>
        <p>The code above loads the module's environment in your script executor's global environment meaning it will be achivable across every script.</p>
        <p>The identificator for the environment is <code>ExunysDeveloperAimbot</code> which is a table that has configurable settings and interactive methods.</p>
        <p>The table loaded into the exploit's global environment by the module has a <em><a href="https://create.roblox.com/docs/scripting/luau/metatables" target="_blank">metatable</a></em> set to it with a <strong>__call</strong> metamethod, meaning you can call the table which would load the Aimbot.</p>
        <pre><code>loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V3/main/src/Aimbot.lua"))()()</code></pre>
        <p>or</p>
        <pre><code>loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V3/main/src/Aimbot.lua"))()
ExunysDeveloperAimbot()</code></pre>
        <p>This is equivalent to the <code>Load</code> method, which is a faster alternative for loading the module.</p>
        <pre><code>ExunysDeveloperAimbot.Load()</code></pre>
        <p>This module has customizable settings and other miscellaneous properties. You can see the configurable settings below.</p>
        
        <details>
            <summary>The module's configurable settings</summary>
            <div class="details-content">
<pre><code>getgenv().ExunysDeveloperAimbot = {
    DeveloperSettings = {
        UpdateMode = "RenderStepped",
        TeamCheckOption = "TeamColor",
        RainbowSpeed = 1 -- Bigger = Slower
    },

    Settings = {
        Enabled = true,

        TeamCheck = false,
        AliveCheck = true,
        WallCheck = false,

        OffsetToMoveDirection = false, -- Prediction
        OffsetIncrement = 15, -- Min: 1; Max: 30 -- Amplitude

        Sensitivity = 0, -- Animation length (in seconds) before fully locking onto target / CFrame Sensitivity
        Sensitivity2 = 3.5, -- mousemoverel Sensitivity

        LockMode = 1, -- 1 = CFrame; 2 = mousemoverel
        LockPart = "Head", -- Body part to lock on

        TriggerKey = Enum.UserInputType.MouseButton2,
        Toggle = false
    },

    FOVSettings = {
        Enabled = true,
        Visible = true,

        Radius = 90, -- Field Of View
        NumSides = 60,

        Thickness = 1,
        Transparency = 1,
        Filled = false,

        RainbowColor = false,
        RainbowOutlineColor = false,
        Color = Color3.fromRGB(255, 255, 255),
        OutlineColor = Color3.fromRGB(0, 0, 0),
        LockedColor = Color3.fromRGB(255, 150, 150)
    }
}</code></pre>
                <div class="note">
                    <p><strong>NOTE:</strong> Do not execute this code, it is attached here as an example, executing this would rewrite the environment and critical core data for the aimbot to function. Instead if you want to change some setting make sure you use the example below:</p>
                </div>
                <div class="code-container">
                    <button class="copy-btn" onclick="copyCode(this)">Copy</button>
                    <pre><code>loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V3/main/src/Aimbot.lua"))()
ExunysDeveloperAimbot.Settings.Enabled = false</code></pre>
                </div>
            </div>
        </details>

        <details>
            <summary>Previews</summary>
            <div class="details-content">
                <h3>The video below showcases the stability and strength of the aim lock and how its perfect for HvH scenarios.</h3>
                <video src="https://github.com/Exunys/Aimbot-V3/assets/76539058/408a4c1e-39fc-4499-9e1d-41aabd4429a0" controls muted playsinline></video>
                
                <h3>The videos below showcases the smoothness of the aim lock and its adjustable style engineered to assist for aiming in any type of game.</h3>
                <video src="https://github.com/Exunys/Aimbot-V3/assets/76539058/8238183a-1594-4ca4-a146-c55c0cf76106" controls muted playsinline></video>
                <video src="https://github.com/Exunys/Aimbot-V3/assets/76539058/b77fe625-aecc-41ed-9543-47460ca2703d" controls muted playsinline></video>
                
                <h3>The video below showcases the <code>Blacklist</code> and <code>Whitelist</code> methods.</h3>
                <video src="https://github.com/Exunys/Aimbot-V3/assets/76539058/5e202703-d86d-4563-af52-f757e43fde39" controls muted playsinline></video>
            </div>
        </details>
    </div>

    <script>
        function copyCode(button) {
            const pre = button.nextElementSibling;
            const code = pre.querySelector('code');
            navigator.clipboard.writeText(code.innerText).then(() => {
                const originalText = button.innerText;
                button.innerText = 'Copied!';
                button.classList.add('copied');
                
                setTimeout(() => {
                    button.innerText = originalText;
                    button.classList.remove('copied');
                }, 2000);
            }).catch(err => {
                console.error('Failed to copy text: ', err);
            });
        }
    </script>
</body>
</html>