<template>
  <div>
    <div class="account-pages my-5 pt-sm-5">
      <div class="container">
        <div class="row align-items-center justify-content-center">
          <div class="col-md-8 col-lg-6 col-xl-5">
            <div class="card">
              <div class="card-body p-4">
                <div class="text-center mt-2">
                  <img
                    src="logo.svg"
                    alt=""
                    height="60"
                    class="logo logo-dark m-auto"
                  />
                  <p class="text-muted mt-2">Sign up to continue.</p>
                </div>
                <div class="p-2 mt-4">
                  <form action="index.html">
                    <div class="mb-3">
                      <label class="form-label" for="username">Username</label>
                      <input
                        type="text"
                        class="form-control"
                        placeholder="Enter username"
                      />
                    </div>
                    <div class="mb-3">
                      <label class="form-label" for="username">Email</label>
                      <input
                        type="email"
                        class="form-control"
                        placeholder="Enter email"
                      />
                    </div>
                    <div class="mb-3">
                      <label class="form-label" for="userpassword"
                        >Password</label
                      >
                      <input
                        type="password"
                        class="form-control"
                        id="userpassword"
                        placeholder="Enter password"
                      />
                    </div>
                    <div class="mb-3">
                      <label class="form-label" for="userpassword"
                        >Confirm Password</label
                      >
                      <input
                        type="password"
                        class="form-control"
                        id="userpassword"
                        placeholder="Enter password"
                      />
                    </div>

                    <div class="mt-3 text-end">
                      <button
                        class="btn btn-primary w-sm waves-effect waves-light"
                        type="submit"
                      >
                        Sign Up
                      </button>
                    </div>

                    <div class="mt-4 text-center">
                      <p class="mb-0">
                        Have account ?
                        <a
                          href="auth-register.html"
                          class="fw-medium text-primary"
                        >
                          Sign In
                        </a>
                      </p>
                      <p class="mb-0">
                        Are you a customer ?
                        <a
                          href="auth-register.html"
                          class="fw-medium text-primary"
                        >
                          Go to shop
                        </a>
                      </p>
                    </div>
                  </form>
                </div>
              </div>
            </div>

            <div class="mt-5 text-center">
              <p>
                ©
                <span>
                  {{ date }}
                </span>
                Fikisha Ltd. Powered By
                <i class="mdi mdi-heart text-danger"></i> Teddy Genial
              </p>
            </div>
          </div>
        </div>
        <!-- end row -->
      </div>
      <!-- end container -->
    </div>
  </div>
</template>

<script>
export default {
  props: [],
  components: {},
  data() {
    return {
      date: new Date().getFullYear(),
    };
  },
};
</script>
