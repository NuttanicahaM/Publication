```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Research Publications | Nuttanicha Muangmool</title>

    <style>

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f5f7fa;
            color: #1f2937;
            line-height: 1.6;
        }

        /* =========================
           HEADER
        ========================= */

        header {
            background: linear-gradient(135deg, #163a5f, #2d6a9f);
            color: white;
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            font-size: 42px;
            margin-bottom: 18px;
            letter-spacing: 1px;
        }

        header .name {
            font-size: 23px;
            font-weight: bold;
            margin-bottom: 5px;
        }

        header p {
            font-size: 18px;
            margin: 3px 0;
        }

        /* =========================
           MAIN
        ========================= */

        main {
            max-width: 1100px;
            margin: 55px auto;
            padding: 0 20px;
        }

        .section-title {
            text-align: center;
            font-size: 30px;
            margin-bottom: 40px;
            color: #163a5f;
        }

        /* =========================
           PUBLICATIONS
        ========================= */

        .publications {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 30px;
        }

        .paper-card {
            background: white;
            border-radius: 16px;
            padding: 35px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);

            display: flex;
            flex-direction: column;

            transition: transform 0.25s ease,
                        box-shadow 0.25s ease;
        }

        .paper-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 12px 30px rgba(0, 0, 0, 0.13);
        }

        .paper-number {
            font-size: 14px;
            font-weight: bold;
            color: #2d6a9f;
            letter-spacing: 2px;
            margin-bottom: 10px;
        }

        .paper-type {
            display: inline-block;
            width: fit-content;

            background: #e8f1f8;
            color: #163a5f;

            padding: 6px 12px;
            border-radius: 20px;

            font-size: 13px;
            font-weight: bold;

            margin-bottom: 18px;
        }

        .paper-card h2 {
            font-size: 22px;
            line-height: 1.45;
            color: #163a5f;
            margin-bottom: 18px;
        }

        .paper-card p {
            color: #5b6470;
            font-size: 15px;
            margin-bottom: 25px;
        }

        /* =========================
           BUTTONS
        ========================= */

        .buttons {
            margin-top: auto;

            display: flex;
            gap: 12px;
            flex-wrap: wrap;
        }

        .button {
            display: inline-block;

            padding: 11px 18px;

            border-radius: 8px;

            text-decoration: none;

            font-weight: bold;

            transition: 0.2s;
        }

        .view-paper {
            background: #163a5f;
            color: white;
        }

        .view-paper:hover {
            background: #0e2944;
        }

        .github {
            background: #eeeeee;
            color: #222;
        }

        .github:hover {
            background: #dddddd;
        }

        /* =========================
           FOOTER
        ========================= */

        footer {
            text-align: center;

            padding: 30px 20px;

            background: #163a5f;

            color: white;

            margin-top: 70px;

            font-size: 14px;
        }

        /* =========================
           MOBILE
        ========================= */

        @media (max-width: 750px) {

            header {
                padding: 55px 20px;
            }

            header h1 {
                font-size: 30px;
            }

            .publications {
                grid-template-columns: 1fr;
            }

            .paper-card {
                padding: 25px;
            }

        }

    </style>

</head>


<body>


    <!-- =========================
         HEADER
    ========================= -->

    <header>

        <h1>
            MY RESEARCH PUBLICATIONS
        </h1>

        <p class="name">
            Nuttanicha Muangmool
        </p>

        <p>
            Biomedical Data Science
        </p>

        <p>
            Kasetsart University
        </p>

    </header>


    <!-- =========================
         PUBLICATIONS
    ========================= -->

    <main>

        <h2 class="section-title">
            RESEARCH PUBLICATIONS
        </h2>


        <div class="publications">


            <!-- =========================
                 PAPER 01
            ========================= -->

            <div class="paper-card">

                <div class="paper-number">
                    PAPER 01
                </div>

                <div class="paper-type">
                    The 9th UTCC National Conference
                </div>

                <h2>
                    Influencing Factors with the Effectiveness of Bone Tumors Treatment in Patients
                </h2>

                <p>
                    Conference publication presenting an analysis of factors
                    influencing the effectiveness of bone tumor treatment in patients.
                </p>

                <div class="buttons">

                    <a
                        href="papers/paper1.pdf"
                        target="_blank"
                        class="button view-paper">

                        📄 View Publication

                    </a>

                    <a
                        href="https://github.com/NuttanicahaM/Publication"
                        target="_blank"
                        class="button github">

                        💻 GitHub

                    </a>

                </div>

            </div>


            <!-- =========================
                 PAPER 02
            ========================= -->

            <div class="paper-card">

                <div class="paper-number">
                    PAPER 02
                </div>

                <div class="paper-type">
                    Master's Thesis
                </div>

                <h2>
                    FACTORS INFLUENCING TREATMENT OUTCOMES IN BONE CANCER
                </h2>

                <p>
                    Master's thesis investigating factors associated with
                    treatment outcomes in patients with bone cancer using
                    statistical analysis and machine learning approaches.
                </p>

                <div class="buttons">

                    <a
                        href="papers/paper2.pdf"
                        target="_blank"
                        class="button view-paper">

                        📄 View Thesis

                    </a>

                    <a
                        href="https://github.com/NuttanicahaM/Publication"
                        target="_blank"
                        class="button github">

                        💻 GitHub

                    </a>

                </div>

            </div>


        </div>

    </main>


    <!-- =========================
         FOOTER
    ========================= -->

    <footer>

        © 2026 Nuttanicha Muangmool · Research Publications

    </footer>


</body>

</html>
```
