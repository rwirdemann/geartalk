<script>
    let selection = {
        brand: 'Gong',
        component: 'Board',
        model: 'Lemon',
        year: '2023',
        size: '4\'9"'
    }

    let onChangeAgeRange = 0

    const onChange = () => {

    }
</script>
<form class="container">
    <div class="row">
        <div class="col">
            <div class="mb-3">
                <label class="form-label">Hersteller</label>
                <div class="input-group">
                    <select bind:value={selection.brand} class="form-select">
                        <option>Fanatic</option>
                        <option>Gong</option>
                        <option>Appletree</option>
                        <option>Vayu</option>
                    </select>
                    <button type="button" class="btn btn-outline-secondary" data-bs-toggle="modal"
                            data-bs-target="#exampleModal">
                        Neu...
                    </button>
                </div>
            </div>
        </div>
        <div class="col">
            <div class="mb-3">
                <label class="form-label">Komponente</label>
                <select bind:value={selection.component} class="form-select">
                    <option>Board</option>
                    <option>Wing</option>
                    <option>Mast</option>
                    <option>Frontwing</option>
                    <option>Rearwing</option>
                </select>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <div class="mb-3">
                <label class="form-label">Modell</label>
                <div class="input-group">
                    <select bind:value={selection.model} class="form-select">
                        <option>Sky Style SLS</option>
                        <option>Lemon</option>
                    </select>
                    <button type="button" class="btn btn-outline-secondary" data-bs-toggle="modal"
                            data-bs-target="#exampleModal">
                        Neu...
                    </button>
                </div>
            </div>
        </div>
        <div class="col-3">
            <div class="mb-3">
                <label class="form-label">Jahr</label>
                <select bind:value={selection.year} class="form-select">
                    <option>2022</option>
                    <option>2023</option>
                    <option>2024</option>
                </select>
            </div>
        </div>
        <div class="col-3">
            <div class="mb-3">
                <label class="form-label">Größe</label>
                <div class="input-group">
                    <select bind:value={selection.size} class="form-select">
                        <option>4'9"</option>
                        <option>5'1"</option>
                    </select>
                    <button type="button" class="btn btn-outline-secondary" data-bs-toggle="modal"
                            data-bs-target="#exampleModal">
                        Neu...
                    </button>
                </div>
            </div>
        </div>

        <div class="mb-3">
            <label for="description" class="form-label">Dein Bericht: {selection.brand} => {selection.component} => {selection.model} => {selection.year} => {selection.size}
            </label>
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