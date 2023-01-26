# Practice-1
My Coding Journey Start Here
<!DOCtype html>
    <html>
        <head>
            <title>Unit Conversion</title>
        </head>

        <body>
            <section id="home">
                <header><b>Unit Conversions</b></header>

                <nav>
                    <a href="#temperature"><button>Temperature</button></a>
                    <a href="#weight"><button>Weight</button></a>
                    <a href="#distance"><button>Distance</button></a>
                </nav>
            </section>
            <div id="all-conversion-sections">
                <section id="temperature">
                    <div id="tmp">
                        <figure>
                            <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/thermo.png" width="200px">
                            <figcaption>Celcius to Fahrenheit Conversion</figcaption>
                        </figure>

                        <article>
                            <fieldset>
                                <legend>Temperature</legend>
                                <label for="Temperature">Celsius</label><br>
                                <input type="number" id="c"><br>
                                <button id="temperature">Convert</button><br>
                                <input type="number" id="f"><br>
                                <label for="Temperature">Fahrenheit</label>
                            </fieldset>
                        </article>
                        <aside>
                            To conver celsius to fahrenheit yourself, use this formula replacing the `C` with your temperature in celsuis: (C × 9/5) + 32
                        </aside>
                    </div>
                </section>
                <section id="weight">
                    <div id="wgt">
                        <figure>
                            <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/weight.png" width="200px">
                            <figcaption>Kilogram to Pound Conversion</figcaption>
                        </figure>

                        <article>
                            <fieldset>
                                <legend>Weight</legend>
                                <label for="Weight">Kilograms</label><br>
                                <input type="number" id="kg"><br>
                                <button id="Weight">Convert</button></br>
                                <input type="number" id="lbs"><br>
                                <label for="Weight">Pounds</label><br>
                            </fieldset>
                        </article>
                        <aside>
                            To convert kilograms to pounds yourself, use this formula replacing the `kg` with your weight in kilograms: kg x 2.205
                        </aside>
                    </div>
                </section>
                <section id="distance">
                    <div id="dst">
                        <figure>
                            <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-CD0101EN-SkillsNetwork/labs/Theia%20Labs/02%20-%20HTML5%20Elements/images/speedo.png" width="200px">
                            <figcaption>Kilometer to Mile Conversion</figcaption>
                        </figure>

                        <article>
                            <fieldset>
                                    <legend>Distance</legend>
                                    <label for="Distance">Kilometers</label><br>
                                    <input type="number" id="km"><br>
                                    <button id="distance">Convert</button><br>
                                    <input type="number" id="m"><br>
                                    <label for="Distance">Miles</label><br>
                            </fieldset>
                        </article>
                        <aside>
                            To convert kilometers to miles yourself, use this formula replacing the `km` with your distance in kilmeters: km &divide; 1.609
                        </aside>
                    </div>
                </section>

            </div>
        </body>
    </html>
