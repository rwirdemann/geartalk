<form class="container-md">
    <div class="row">
        <div class="col">
            <div class="mb-3">
                <label class="form-label">Report über</label>
                <select class="form-select">
                    <option>Board</option>
                    <option>Wing</option>
                    <option>Mast</option>
                    <option>Frontwing</option>
                    <option>Rearwing</option>
                </select>
            </div>
        </div>
        <div class="col">
            <div class="mb-3">
                <label class="form-label">Hersteller</label>
                <div class="input-group">
                    <select class="form-select">
                        <option>Fanatic</option>
                        <option>Gong</option>
                        <option>Appletree</option>
                        <option>Vayu</option>
                    </select>
                    <button type="button" class="btn btn-outline-secondary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                        Neu...
                    </button>
                </div>
            </div>
        </div>
        <div class="mb-3">
            <label for="description" class="form-label">Dein Bericht</label>
            <textarea class="form-control" id="description" rows="5"></textarea>
        </div>
    </div>
    <button type="submit" class="btn btn-primary">Report einstellen</button>
</form>

<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <h1 class="modal-title fs-5" id="exampleModalLabel">Modal title</h1>
                <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
            </div>
            <div class="modal-body">
                ...
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                <button type="button" class="btn btn-primary">Save changes</button>
            </div>
        </div>
    </div>
</div>