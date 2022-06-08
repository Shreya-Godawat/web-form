<template>
  <form>
    <div class="mb-3">
      <h2>Sign Up</h2>
    </div>
    <div class="mb-3">
      <label for="inputLanguage" class="form-label bold">Language</label>
      <select id="inputLanguage" class="form-select form-control" required>
        <option selected>Choose...</option>
        <option value="English">English</option>
        <option value="Hindi">Hindi</option>
      </select>
    </div>
    <div class="mb-3">
      <label for="floatingInputValue" class="form-label bold">Headline</label>
      <input
        type="text"
        class="form-control"
        id="floatingInputValue"
        placeholder="Headline"
        required
      />
    </div>
    <div class="mb-3">
      <label for="floatingTextarea2" class="form-label bold"
        >Tell us about yourself</label
      >
      <textarea
        class="form-control"
        placeholder="Describe yourself"
        id="floatingTextarea2"
        style="height: 100px"
        required
      ></textarea>
    </div>
    <br /><br />
    <div class="d-grid footer">
      <button class="btn btn-primary" type="button">Save & Next</button>
    </div>
  </form>
</template>