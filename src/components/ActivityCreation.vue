<template>
  <form action="">
    <div class="mb-3">
      <h2>Activity Creation</h2>
    </div>
    <div class="mb-3">
      <label for="title" class="form-label bold">Title</label>
      <input
        type="text"
        class="form-control"
        id="title"
        placeholder="Activity title"
        v-model="title"
        required
      />
    </div>
    <div class="mb-3">
      <label for="details" class="form-label bold">Details</label>
      <textarea
        class="form-control"
        placeholder="Describe the activity in detail(min. 100 words)"
        id="details"
        style="height: 100px"
        v-model="details"
        required
      ></textarea>
    </div>
    <div class="mb-3">
      <label for="token" class="form-label bold">Tokens</label>
      <input
        type="number"
        class="form-control"
        id="token"
        v-model="token"
        required
      />
    </div>
    <div class="fs-4 mb-2">
      <label for="image" class="form-label bold">Images</label>
      <label class="right">
        <input type="file" id="image" hidden required />
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="25"
          height="25"
          fill="currentColor"
          class="bi bi-camera-fill"
          viewBox="0 0 16 16"
        >
          <path d="M10.5 8.5a2.5 2.5 0 1 1-5 0 2.5 2.5 0 0 1 5 0z"></path>
          <path
            d="M2 4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-1.172a2 2 0 0 1-1.414-.586l-.828-.828A2 2 0 0 0 9.172 2H6.828a2 2 0 0 0-1.414.586l-.828.828A2 2 0 0 1 3.172 4H2zm.5 2a.5.5 0 1 1 0-1 .5.5 0 0 1 0 1zm9 2.5a3.5 3.5 0 1 1-7 0 3.5 3.5 0 0 1 7 0z"
          ></path>
        </svg>
      </label>
    </div>
    <div class="fs-4 mb-2">
      <label for="video" class="form-label bold">Videos</label>
      <label class="right">
        <input type="file" id="video" hidden required />
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          fill="currentColor"
          class="bi bi-camera-reels-fill"
          viewBox="0 0 16 16"
        >
          <path d="M6 3a3 3 0 1 1-6 0 3 3 0 0 1 6 0z" />
          <path d="M9 6a3 3 0 1 1 0-6 3 3 0 0 1 0 6z" />
          <path
            d="M9 6h.5a2 2 0 0 1 1.983 1.738l3.11-1.382A1 1 0 0 1 16 7.269v7.462a1 1 0 0 1-1.406.913l-3.111-1.382A2 2 0 0 1 9.5 16H2a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h7z"
          />
        </svg>
      </label>
    </div>
    <div class="mb-3">
      <label for="start_date" class="form-label bold">Start Date</label>
      <input type="date" class="form-control" id="start_date" name="start" />
    </div>
    <div class="mb-3">
      <label for="end_date" class="form-label bold">Event deadline</label>
      <input type="date" class="form-control" id="end_date" name="end" />
    </div>
    <br><br>
    <div class="d-grid footer">
      <button class="btn btn-primary" type="button">Create</button>
    </div>
  </form>
</template>