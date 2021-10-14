# apiTestVMresources211009
api test resource


Use fetch code

<html>
    <head></head>
    <body>
        Using the console
        <script>
            //fetch('https://reqres.in/api/users')
            fetch('https://api211009.herokuapp.com/schem')
            .then(res => res.json())
            .then(data => console.log(data))


        </script>
    </body>
</html>
