<template>
  <form>
    <div class="mb-3">
      <h2>Sign Up</h2>
    </div>
    <div class="mb-3">
      <label for="birthday" class="form-label bold">Date of Birth</label>
      <input type="date" class="form-control" id="birthday" name="birthday" required/>
    </div>
    <div class="mb-3">
      <label class="form-label bold">Gender</label>
      <br />
      <div class="form-check form-check-inline">
        <input
          class="form-check-input"
          type="radio"
          name="inlineRadioOptions"
          id="inlineRadio1"
          value="male"
        />
        <label class="form-check-label" for="inlineRadio1">Male</label>
      </div>
      <div class="form-check form-check-inline">
        <input
          class="form-check-input"
          type="radio"
          name="inlineRadioOptions"
          id="inlineRadio2"
          value="female"
        />
        <label class="form-check-label" for="inlineRadio2">Female</label>
      </div>
      <div class="form-check form-check-inline">
        <input
          class="form-check-input"
          type="radio"
          name="inlineRadioOptions"
          id="inlineRadio3"
          value="other"
        />
        <label class="form-check-label" for="inlineRadio3">Other</label>
      </div>
    </div>
    <div class="mb-3">
      <label for="phoneNumber" class="form-label bold">Phone number</label>
      <input
        class="form-control"
        type="tel"
        pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
        id="phoneNumber"
        placeholder="+919991029912"
        required
      />
    </div>
    <div class="mb-3">
      <label for="inputAddress" class="form-label bold">Address</label>
      <input
        type="text"
        class="form-control"
        id="inputAddress"
        placeholder="1234 Main St"
      />
    </div>
    <div class="mb-3">
      <label for="inputAddress2" class="form-label bold">Address2</label>
      <input
        type="text"
        class="form-control"
        id="inputAddress2"
        placeholder="Apartment, studio, or floor"
        required
      />
    </div>
    <div class="mb-3">
      <label for="inputCity" class="form-label bold"
        >Village/District/City</label
      >
      <input
        type="text"
        class="form-control"
        id="inputCity"
        placeholder="Surat"
        required
      />
    </div>
    <div class="mb-3">
      <label for="inputZip" class="form-label bold">Pin Code</label>
      <input
        type="text"
        class="form-control"
        id="inputZip"
        placeholder="122012"
        required
      />
    </div>
    <div class="mb-3">
      <label for="inputCountry" class="form-label bold">Country</label>
      <br />
      <select id="inputCountry" class="form-select form-control" required>
        <option selected>Choose...</option>
        <option value="India">India</option>
        <option value="United States of America">
          United States of America
        </option>
      </select>
    </div>
    <br /><br />
    <!-- <div class="card">
      <div class="card-body d-grid gap-2"> -->
    <div class="d-grid footer">
      <button class="btn btn-primary" type="button">Save & Next</button>
    </div>
    <!-- </div>
    </div> -->
  </form>
</template>