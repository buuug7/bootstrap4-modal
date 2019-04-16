# bootstrap 4 modal 

extract the bootstrap 4 modal component

## usage

```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
    <title>Document</title>
    <script src="./node_modules/jquery/dist/jquery.js"></script>
    <script src="dist/bootstrap-modal.js"></script>
</head>
<body>

    <button data-toggle="modal" data-target="#exampleModal">
        Launch demo modal
    </button>
    <!-- Modal -->
    <div class="modal fade" id="exampleModal">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
                    <button data-dismiss="modal"><span>&times;</span></button>
                </div>
                <div class="modal-body">
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                </div>
                <div class="modal-footer">
                    <button data-dismiss="modal">Close</button>
                    <button>Save changes</button>
                </div>
            </div>
        </div>
    </div>

</body>
</html>

```