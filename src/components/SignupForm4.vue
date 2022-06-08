<template>
    <form>
        <div class="mb-3">
            <h2>Sign Up</h2>
        </div>
        <div class="fs-4 mb-2">
            <label class="form-label bold">My profile picture</label>
            <label class="right">
                <input type="file" hidden>
                <!-- <button type="button" class="btn btn-primary btn-circle btn-sm" href="#" role="button"> -->
                <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor"
                    class="bi bi-camera-fill" viewBox="0 0 16 16">
                    <path d="M10.5 8.5a2.5 2.5 0 1 1-5 0 2.5 2.5 0 0 1 5 0z"></path>
                    <path
                        d="M2 4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-1.172a2 2 0 0 1-1.414-.586l-.828-.828A2 2 0 0 0 9.172 2H6.828a2 2 0 0 0-1.414.586l-.828.828A2 2 0 0 1 3.172 4H2zm.5 2a.5.5 0 1 1 0-1 .5.5 0 0 1 0 1zm9 2.5a3.5 3.5 0 1 1-7 0 3.5 3.5 0 0 1 7 0z">
                    </path>
                </svg>
            </label>
            <!-- </button> -->
        </div>
        <!--         
        <div class="input-group mb-3">
            <input type="file" class="form-control" id="inputGroupFile02">
        </div> -->
        <div class="mb-3">
            <label for="education" class="form-label bold">Education</label>
            <input type="text" class="form-control" id="education" placeholder="Education">
        </div>
        <div class="mb-3">
            <label for="industry" class="form-label bold">Industry</label>
            <input type="text" class="form-control" id="industry" placeholder="Industry">
        </div>
        <div class="mb-3">
            <label for="website" class="form-label bold">Website</label>
            <input type="url" class="form-control" id="website" placeholder="Website">
        </div>
        <br><br>
        <div class="footer d-grid">
            <button type="submit" class="btn btn-primary">Sign Up</button>
        </div>
    </form>
</template>