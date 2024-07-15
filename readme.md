1. Add columns
2. divide into sections using the <section>
3. Add headers <Header>
4. Add footers <Footer>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header, footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 1rem;
        }
        .columns {
            display: flex;
            gap: 1rem;
        }
        .column {
            flex: 1;
            background-color: #f4f4f4;
            padding: 1rem;
            border: 1px solid #ddd;
        }
        section {
            margin: 2rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Landing Page Header</h1>
    </header>
    
    <div class="container">
        <section>
            <h2>Section 1</h2>
            <div class="columns">
                <div class="column">
                    <h3>Column 1</h3>
                    <p>This is column 1 content.</p>
                </div>
                <div class="column">
                    <h3>Column 2</h3>
                    <p>This is column 2 content.</p>
                </div>
                <div class="column">
                    <h3>Column 3</h3>
                    <p>This is column 3 content.</p>
                </div>
            </div>
        </section>
        
        <section>
            <h2>Section 2</h2>
            <div class="columns">
                <div class="column">
                    <h3>Column 1</h3>
                    <p>This is column 1 content.</p>
                </div>
                <div class="column">
                    <h3>Column 2</h3>
                    <p>This is column 2 content.</p>
                </div>
                <div class="column">
                    <h3>Column 3</h3>
                    <p>This is column 3 content.</p>
                </div>
            </div>
        </section>
    </div>
    
    <footer>
        <p>Landing Page Footer</p>
    </footer>
</body>
</html>
