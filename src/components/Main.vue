

<template>
  <div class="hello">
    <main class="page payment-page">
      <section class="payment-form">
        <div class="container pt-5">
          <ul class="payment-ul">
            <li class="payment-li">
              <a href="#"> <b> Trips </b></a>
            </li>
            <li class="payment-li">
              <a href="#"> <b> Recent Viewed </b></a>
            </li>
            <li class="payment-li">
              <a href="#"> <b> Boookings </b></a>
            </li>
            <li class="payment-li">
              <i class="far fa-user"></i>
            </li>
          </ul>
        </div>
        <div class="container">
          <div class="block-heading"></div>
          <hr />
          <div class="row">
            <div class="col-md-6 mb-4 center left-cad">
              <h3><b>Payment Information</b></h3>
              <p>Choose Your Method of Payment</p>
            </div>
            <div class="col-md-6">
              <div class="center">
                <ul class="row center">
                  <div class="cadd">
                    <input
                      type="checkbox"
                      id="vehicle1"
                      name="vehicle1"
                      value="Bike"
                    />
                    <label for="vehicle1"> Mastercard </label><br />
                  </div>

                  <div class="cadd">
                    <input
                      type="checkbox"
                      id="vehicle1"
                      name="vehicle1"
                      value="Bike"
                    />
                    <label for="vehicle1"> Visa Card </label><br />
                  </div>

                  <div class="cadd">
                    <input
                      type="checkbox"
                      id="vehicle1"
                      name="vehicle1"
                      value="Bike"
                    />
                    <label for="vehicle1"> Pay Pal </label><br />
                  </div>
                </ul>
              </div>
            </div>
            <hr />
          </div>
          <div class="row">
            <div class="col-md-6 mb-4 card-1 center">
              <img
                alt="Vue logo"
                width="100%"
                src="../assets/Credit-Card-PNG-Pic.png"
              />
            </div>
            <div class="col-md-6">
              <form>
                <div class="card-details">
                  <br /><br /><br />
                  <div class="row">
                    <div class="form-group col-sm-7">
                      <label for="card-holder"><b>Credit Card Number</b></label>
                      <input
                        id="card-holder"
                        type="text"
                        class="form-control"
                        placeholder="4023 5433 99992 1010"
                        aria-label="Card Holder"
                        aria-describedby="basic-addon1"
                      />
                    </div>
                    <div class="form-group col-sm-5">
                      <label for=""><b>Expiration Date</b></label>
                      <div class="input-group expiration-date">
                        <input
                          type="text"
                          class="form-control"
                          placeholder="03"
                          aria-label="MM"
                          aria-describedby="basic-addon1"
                        />
                        <span class="date-separator">/</span>
                        <input
                          type="text"
                          class="form-control"
                          placeholder="24"
                          aria-label="YY"
                          aria-describedby="basic-addon1"
                        />
                      </div>
                    </div>
                    <div class="form-group col-sm-8">
                      <label for="card-number"><b>Security Code</b></label>
                      <input
                        id="card-number"
                        type="text"
                        class="form-control"
                        placeholder="420"
                        aria-label="Card Holder"
                        aria-describedby="basic-addon1"
                      />
                    </div>
                    <div class="form-group col-sm-4">
                      <label for="Postal Code"><b>Postal Code</b></label>
                      <input
                        id="Postal Code"
                        type="text"
                        class="form-control"
                        placeholder="10119"
                        aria-label="Card Holder"
                        aria-describedby="basic-addon1"
                      />
                    </div>
                    <div class="form-group col-sm-12">
                      <input
                        type="checkbox"
                        id="vehicle1"
                        name="vehicle1"
                        value="Bike"
                      />
                      <label for="vehicle1">
                        <b>Use this card for next time purcase</b></label
                      ><br />
                    </div>
                    <div class="form-group col-sm-12">
                      <button type="button" class="btn btn-primary btn-block">
                        Add Card
                      </button>
                    </div>
                  </div>
                </div>
              </form>
            </div>
            <hr />
          </div>
          <hr />
          <div class="row">
            <div class="col-md-12 mb-4 center left-span">
              <div style="text-align: left">
                <br />
                <br />
                <p>
                  <b>Sub Total </b
                  ><span class="right-span"><b>#2,497.00</b></span>
                </p>

                <p>
                  <b>Estimated Tax</b
                  ><span class="right-span"><b>#1119.64</b></span>
                </p>
                <p>
                  <b>Promotion Code:</b> Z4KXLM9A<span class="right-span"
                    ><b>-#60.00</b></span
                  >
                </p>
              </div>
            </div>
            <hr />
          </div>
          <hr />
          <div class="row">
            <div class="col-md-6 mb-4 center">
              <div class="form-group col-sm-5">
                <button type="button" class="btn btn-primary btn-block">
                  Complete Payment
                </button>
              </div>
            </div>
            <div class="col-md-6">
              <div style="text-align: right">
                <b>
                  <p>Total: #2556.64</p>
                </b>
              </div>
            </div>
            <hr />
          </div>
        </div>
      </section>
    </main>
    <footer class="container">
      <p>NCKTech Interview Assessment Solution</p>
      <p>
        <a
          href="https://wa.me/2348109342339?text=Hi!%2C%20"
          target="_blank"
          rel="noopener noreferrer"
          >Naija Webmaster</a
        >
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="../assets/css/style.css">
</style>
