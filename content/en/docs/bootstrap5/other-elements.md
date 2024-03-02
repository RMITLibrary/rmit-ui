---
title: "Other Elements"
description: "Other Elements"
lead: "Other Elements"
date: 2020-10-06T08:49:31+00:00
lastmod: 2020-10-06T08:49:31+00:00
draft: false
images: []
menu:
  docs:
    parent: "components"
weight: 700
toc: true
---


## About this page

This page borrows sections from the Bootstrap 5.x documentation [here](https://getbootstrap.com/docs/5.3/getting-started/introduction/). Copied and converted sections of markdown are to show an example of the direct rendering of native bootstrap elements. Some have not been styled

## Accordions

The below code copied from [here](https://getbootstrap.com/docs/5.3/components/accordion/).

<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>

#### Code

```html
<div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>
```

## Breadcrumbs

The below code copied from [here](https://getbootstrap.com/docs/5.3/components/breadcrumb/).

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item active" aria-current="page">Home</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item active" aria-current="page">Library</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item"><a href="#">Library</a></li>
    <li class="breadcrumb-item active" aria-current="page">Data</li>
  </ol>
</nav>

#### Code

```html
<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item active" aria-current="page">Home</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item active" aria-current="page">Library</li>
  </ol>
</nav>

<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item"><a href="#">Library</a></li>
    <li class="breadcrumb-item active" aria-current="page">Data</li>
  </ol>
</nav>
```

## Forms


<section id="forms">
    <article class="my-3" id="overview">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Overview</h3>
        </div>
        <div>
            <div class="bd-example">
                <form>
                    <div class="mb-3"> <label for="exampleInputEmail1" class="form-label">Email address</label> <input
                            type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                        <div id="emailHelp" class="form-text">We’ll never share your email with anyone else.</div>
                    </div>
                    <div class="mb-3"> <label for="exampleInputPassword1" class="form-label">Password</label> <input
                            type="password" class="form-control" id="exampleInputPassword1"></div>
                    <div class="mb-3 form-check"> <input type="checkbox" class="form-check-input" id="exampleCheck1">
                        <label class="form-check-label" for="exampleCheck1">Check me out</label></div>
                    <fieldset class="mb-3">
                        <legend>Radios buttons</legend>
                        <div class="form-check"> <input type="radio" name="radios" class="form-check-input"
                                id="exampleRadio1"> <label class="form-check-label" for="exampleRadio1">Default
                                radio</label></div>
                        <div class="mb-3 form-check"> <input type="radio" name="radios" class="form-check-input"
                                id="exampleRadio2"> <label class="form-check-label" for="exampleRadio2">Another
                                radio</label></div>
                    </fieldset>
                    <div class="mb-3"> <label class="form-label" for="customFile">Upload</label> <input type="file"
                            class="form-control" id="customFile"></div>
                    <div class="mb-3 form-check form-switch"> <input class="form-check-input" type="checkbox"
                            id="flexSwitchCheckChecked" checked=""> <label class="form-check-label"
                            for="flexSwitchCheckChecked">Checked switch checkbox input</label></div>
                    <div class="mb-3"> <label for="customRange3" class="form-label">Example range</label> <input
                            type="range" class="form-range" min="0" max="5" step="0.5" id="customRange3"></div> <button
                        type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </article>
    <article class="my-3" id="disabled-forms">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Disabled forms</h3>
        </div>
        <div>
            <div class="bd-example">
                <form>
                    <fieldset disabled="" aria-label="Disabled fieldset example">
                        <div class="mb-3"> <label for="disabledTextInput" class="form-label">Disabled input</label>
                            <input type="text" id="disabledTextInput" class="form-control" placeholder="Disabled input">
                        </div>
                        <div class="mb-3"> <label for="disabledSelect" class="form-label">Disabled select menu</label>
                            <select id="disabledSelect" class="form-select">
                                <option>Disabled select</option>
                            </select></div>
                        <div class="mb-3">
                            <div class="form-check"> <input class="form-check-input" type="checkbox"
                                    id="disabledFieldsetCheck" disabled=""> <label class="form-check-label"
                                    for="disabledFieldsetCheck"> Can’t check this </label></div>
                        </div>
                        <fieldset class="mb-3">
                            <legend>Disabled radios buttons</legend>
                            <div class="form-check"> <input type="radio" name="radios" class="form-check-input"
                                    id="disabledRadio1" disabled=""> <label class="form-check-label"
                                    for="disabledRadio1">Disabled radio</label></div>
                            <div class="mb-3 form-check"> <input type="radio" name="radios" class="form-check-input"
                                    id="disabledRadio2" disabled=""> <label class="form-check-label"
                                    for="disabledRadio2">Another radio</label></div>
                        </fieldset>
                        <div class="mb-3"> <label class="form-label" for="disabledCustomFile">Upload</label> <input
                                type="file" class="form-control" id="disabledCustomFile" disabled=""></div>
                        <div class="mb-3 form-check form-switch"> <input class="form-check-input" type="checkbox"
                                id="disabledSwitchCheckChecked" checked="" disabled=""> <label class="form-check-label"
                                for="disabledSwitchCheckChecked">Disabled checked switch checkbox input</label></div>
                        <div class="mb-3"> <label for="disabledRange" class="form-label">Disabled range</label> <input
                                type="range" class="form-range" min="0" max="5" step="0.5" id="disabledRange"></div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </fieldset>
                </form>
            </div>
        </div>
    </article>
    <article class="my-3" id="sizing">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Sizing</h3>
        </div>
        <div>
            <div class="bd-example">
                <div class="mb-3"> <input class="form-control form-control-lg" type="text"
                        placeholder=".form-control-lg" aria-label=".form-control-lg example"></div>
                <div class="mb-3"> <select class="form-select form-select-lg mb-3" aria-label=".form-select-lg example">
                        <option selected="">Open this select menu</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                    </select></div>
                <div class="mb-3"> <input type="file" class="form-control form-control-lg"
                        aria-label="Large file input example"></div>
            </div>
            <div class="bd-example">
                <div class="mb-3"> <input class="form-control form-control-sm" type="text"
                        placeholder=".form-control-sm" aria-label=".form-control-sm example"></div>
                <div class="mb-3"> <select class="form-select form-select-sm" aria-label=".form-select-sm example">
                        <option selected="">Open this select menu</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                    </select></div>
                <div class="mb-3"> <input type="file" class="form-control form-control-sm"
                        aria-label="Small file input example"></div>
            </div>
        </div>
    </article>
    <article class="my-3" id="input-group">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Input group</h3>
        </div>
        <div>
            <div class="bd-example">
                <div class="input-group mb-3"> <span class="input-group-text" id="basic-addon1">@</span> <input
                        type="text" class="form-control" placeholder="Username" aria-label="Username"
                        aria-describedby="basic-addon1"></div>
                <div class="input-group mb-3"> <input type="text" class="form-control"
                        placeholder="Recipient's username" aria-label="Recipient's username"
                        aria-describedby="basic-addon2"> <span class="input-group-text"
                        id="basic-addon2">@example.com</span></div> <label for="basic-url" class="form-label">Your
                    vanity URL</label>
                <div class="input-group mb-3"> <span class="input-group-text"
                        id="basic-addon3">https://example.com/users/</span> <input type="text" class="form-control"
                        id="basic-url" aria-describedby="basic-addon3"></div>
                <div class="input-group mb-3"> <span class="input-group-text">$</span> <input type="text"
                        class="form-control" aria-label="Amount (to the nearest dollar)"> <span
                        class="input-group-text">.00</span></div>
                <div class="input-group"> <span class="input-group-text">With textarea</span><textarea
                        class="form-control" aria-label="With textarea"></textarea></div>
            </div>
        </div>
    </article>
    <article class="my-3" id="floating-labels">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Floating labels</h3>
        </div>
        <div>
            <div class="bd-example">
                <form>
                    <div class="form-floating mb-3"> <input type="email" class="form-control" id="floatingInput"
                            placeholder="name@example.com"> <label for="floatingInput">Email address</label></div>
                    <div class="form-floating"> <input type="password" class="form-control" id="floatingPassword"
                            placeholder="Password"> <label for="floatingPassword">Password</label></div>
                </form>
            </div>
        </div>
    </article>
    <article class="my-3" id="validation">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Validation</h3>
        </div>
        <div>
            <div class="bd-example">
                <form class="row g-3">
                    <div class="col-md-4"> <label for="validationServer01" class="form-label">First name</label> <input
                            type="text" class="form-control is-valid" id="validationServer01" value="Mark" required="">
                        <div class="valid-feedback"> Looks good!</div>
                    </div>
                    <div class="col-md-4"> <label for="validationServer02" class="form-label">Last name</label> <input
                            type="text" class="form-control is-valid" id="validationServer02" value="Otto" required="">
                        <div class="valid-feedback"> Looks good!</div>
                    </div>
                    <div class="col-md-4"> <label for="validationServerUsername" class="form-label">Username</label>
                        <div class="input-group has-validation"> <span class="input-group-text"
                                id="inputGroupPrepend3">@</span> <input type="text" class="form-control is-invalid"
                                id="validationServerUsername" aria-describedby="inputGroupPrepend3" required="">
                            <div class="invalid-feedback"> Please choose a username.</div>
                        </div>
                    </div>
                    <div class="col-md-6"> <label for="validationServer03" class="form-label">City</label> <input
                            type="text" class="form-control is-invalid" id="validationServer03" required="">
                        <div class="invalid-feedback"> Please provide a valid city.</div>
                    </div>
                    <div class="col-md-3"> <label for="validationServer04" class="form-label">State</label> <select
                            class="form-select is-invalid" id="validationServer04" required="">
                            <option selected="" disabled="" value="">Choose…</option>
                            <option>…</option>
                        </select>
                        <div class="invalid-feedback"> Please select a valid state.</div>
                    </div>
                    <div class="col-md-3"> <label for="validationServer05" class="form-label">Zip</label> <input
                            type="text" class="form-control is-invalid" id="validationServer05" required="">
                        <div class="invalid-feedback"> Please provide a valid zip.</div>
                    </div>
                    <div class="col-12">
                        <div class="form-check"> <input class="form-check-input is-invalid" type="checkbox" value=""
                                id="invalidCheck3" required=""> <label class="form-check-label" for="invalidCheck3">
                                Agree to terms and conditions </label>
                            <div class="invalid-feedback"> You must agree before submitting.</div>
                        </div>
                    </div>
                    <div class="col-12"> <button class="btn btn-primary" type="submit">Submit form</button></div>
                </form>
            </div>
        </div>
    </article>
</section>

```html 
<section id="forms">
    <article class="my-3" id="overview">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Overview</h3>
        </div>
        <div>
            <div class="bd-example">
                <form>
                    <div class="mb-3"> <label for="exampleInputEmail1" class="form-label">Email address</label> <input
                            type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                        <div id="emailHelp" class="form-text">We’ll never share your email with anyone else.</div>
                    </div>
                    <div class="mb-3"> <label for="exampleInputPassword1" class="form-label">Password</label> <input
                            type="password" class="form-control" id="exampleInputPassword1"></div>
                    <div class="mb-3 form-check"> <input type="checkbox" class="form-check-input" id="exampleCheck1">
                        <label class="form-check-label" for="exampleCheck1">Check me out</label></div>
                    <fieldset class="mb-3">
                        <legend>Radios buttons</legend>
                        <div class="form-check"> <input type="radio" name="radios" class="form-check-input"
                                id="exampleRadio1"> <label class="form-check-label" for="exampleRadio1">Default
                                radio</label></div>
                        <div class="mb-3 form-check"> <input type="radio" name="radios" class="form-check-input"
                                id="exampleRadio2"> <label class="form-check-label" for="exampleRadio2">Another
                                radio</label></div>
                    </fieldset>
                    <div class="mb-3"> <label class="form-label" for="customFile">Upload</label> <input type="file"
                            class="form-control" id="customFile"></div>
                    <div class="mb-3 form-check form-switch"> <input class="form-check-input" type="checkbox"
                            id="flexSwitchCheckChecked" checked=""> <label class="form-check-label"
                            for="flexSwitchCheckChecked">Checked switch checkbox input</label></div>
                    <div class="mb-3"> <label for="customRange3" class="form-label">Example range</label> <input
                            type="range" class="form-range" min="0" max="5" step="0.5" id="customRange3"></div> <button
                        type="submit" class="btn btn-primary">Submit</button>
                </form>
            </div>
        </div>
    </article>
    <article class="my-3" id="disabled-forms">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Disabled forms</h3>
        </div>
        <div>
            <div class="bd-example">
                <form>
                    <fieldset disabled="" aria-label="Disabled fieldset example">
                        <div class="mb-3"> <label for="disabledTextInput" class="form-label">Disabled input</label>
                            <input type="text" id="disabledTextInput" class="form-control" placeholder="Disabled input">
                        </div>
                        <div class="mb-3"> <label for="disabledSelect" class="form-label">Disabled select menu</label>
                            <select id="disabledSelect" class="form-select">
                                <option>Disabled select</option>
                            </select></div>
                        <div class="mb-3">
                            <div class="form-check"> <input class="form-check-input" type="checkbox"
                                    id="disabledFieldsetCheck" disabled=""> <label class="form-check-label"
                                    for="disabledFieldsetCheck"> Can’t check this </label></div>
                        </div>
                        <fieldset class="mb-3">
                            <legend>Disabled radios buttons</legend>
                            <div class="form-check"> <input type="radio" name="radios" class="form-check-input"
                                    id="disabledRadio1" disabled=""> <label class="form-check-label"
                                    for="disabledRadio1">Disabled radio</label></div>
                            <div class="mb-3 form-check"> <input type="radio" name="radios" class="form-check-input"
                                    id="disabledRadio2" disabled=""> <label class="form-check-label"
                                    for="disabledRadio2">Another radio</label></div>
                        </fieldset>
                        <div class="mb-3"> <label class="form-label" for="disabledCustomFile">Upload</label> <input
                                type="file" class="form-control" id="disabledCustomFile" disabled=""></div>
                        <div class="mb-3 form-check form-switch"> <input class="form-check-input" type="checkbox"
                                id="disabledSwitchCheckChecked" checked="" disabled=""> <label class="form-check-label"
                                for="disabledSwitchCheckChecked">Disabled checked switch checkbox input</label></div>
                        <div class="mb-3"> <label for="disabledRange" class="form-label">Disabled range</label> <input
                                type="range" class="form-range" min="0" max="5" step="0.5" id="disabledRange"></div>
                        <button type="submit" class="btn btn-primary">Submit</button>
                    </fieldset>
                </form>
            </div>
        </div>
    </article>
    <article class="my-3" id="sizing">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Sizing</h3>
        </div>
        <div>
            <div class="bd-example">
                <div class="mb-3"> <input class="form-control form-control-lg" type="text"
                        placeholder=".form-control-lg" aria-label=".form-control-lg example"></div>
                <div class="mb-3"> <select class="form-select form-select-lg mb-3" aria-label=".form-select-lg example">
                        <option selected="">Open this select menu</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                    </select></div>
                <div class="mb-3"> <input type="file" class="form-control form-control-lg"
                        aria-label="Large file input example"></div>
            </div>
            <div class="bd-example">
                <div class="mb-3"> <input class="form-control form-control-sm" type="text"
                        placeholder=".form-control-sm" aria-label=".form-control-sm example"></div>
                <div class="mb-3"> <select class="form-select form-select-sm" aria-label=".form-select-sm example">
                        <option selected="">Open this select menu</option>
                        <option value="1">One</option>
                        <option value="2">Two</option>
                        <option value="3">Three</option>
                    </select></div>
                <div class="mb-3"> <input type="file" class="form-control form-control-sm"
                        aria-label="Small file input example"></div>
            </div>
        </div>
    </article>
    <article class="my-3" id="input-group">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Input group</h3>
        </div>
        <div>
            <div class="bd-example">
                <div class="input-group mb-3"> <span class="input-group-text" id="basic-addon1">@</span> <input
                        type="text" class="form-control" placeholder="Username" aria-label="Username"
                        aria-describedby="basic-addon1"></div>
                <div class="input-group mb-3"> <input type="text" class="form-control"
                        placeholder="Recipient's username" aria-label="Recipient's username"
                        aria-describedby="basic-addon2"> <span class="input-group-text"
                        id="basic-addon2">@example.com</span></div> <label for="basic-url" class="form-label">Your
                    vanity URL</label>
                <div class="input-group mb-3"> <span class="input-group-text"
                        id="basic-addon3">https://example.com/users/</span> <input type="text" class="form-control"
                        id="basic-url" aria-describedby="basic-addon3"></div>
                <div class="input-group mb-3"> <span class="input-group-text">$</span> <input type="text"
                        class="form-control" aria-label="Amount (to the nearest dollar)"> <span
                        class="input-group-text">.00</span></div>
                <div class="input-group"> <span class="input-group-text">With textarea</span><textarea
                        class="form-control" aria-label="With textarea"></textarea></div>
            </div>
        </div>
    </article>
    <article class="my-3" id="floating-labels">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Floating labels</h3>
        </div>
        <div>
            <div class="bd-example">
                <form>
                    <div class="form-floating mb-3"> <input type="email" class="form-control" id="floatingInput"
                            placeholder="name@example.com"> <label for="floatingInput">Email address</label></div>
                    <div class="form-floating"> <input type="password" class="form-control" id="floatingPassword"
                            placeholder="Password"> <label for="floatingPassword">Password</label></div>
                </form>
            </div>
        </div>
    </article>
    <article class="my-3" id="validation">
        <div class="bd-heading align-self-start mt-5 mb-3 mt-xl-0 mb-xl-2">
            <h3>Validation</h3>
        </div>
        <div>
            <div class="bd-example">
                <form class="row g-3">
                    <div class="col-md-4"> <label for="validationServer01" class="form-label">First name</label> <input
                            type="text" class="form-control is-valid" id="validationServer01" value="Mark" required="">
                        <div class="valid-feedback"> Looks good!</div>
                    </div>
                    <div class="col-md-4"> <label for="validationServer02" class="form-label">Last name</label> <input
                            type="text" class="form-control is-valid" id="validationServer02" value="Otto" required="">
                        <div class="valid-feedback"> Looks good!</div>
                    </div>
                    <div class="col-md-4"> <label for="validationServerUsername" class="form-label">Username</label>
                        <div class="input-group has-validation"> <span class="input-group-text"
                                id="inputGroupPrepend3">@</span> <input type="text" class="form-control is-invalid"
                                id="validationServerUsername" aria-describedby="inputGroupPrepend3" required="">
                            <div class="invalid-feedback"> Please choose a username.</div>
                        </div>
                    </div>
                    <div class="col-md-6"> <label for="validationServer03" class="form-label">City</label> <input
                            type="text" class="form-control is-invalid" id="validationServer03" required="">
                        <div class="invalid-feedback"> Please provide a valid city.</div>
                    </div>
                    <div class="col-md-3"> <label for="validationServer04" class="form-label">State</label> <select
                            class="form-select is-invalid" id="validationServer04" required="">
                            <option selected="" disabled="" value="">Choose…</option>
                            <option>…</option>
                        </select>
                        <div class="invalid-feedback"> Please select a valid state.</div>
                    </div>
                    <div class="col-md-3"> <label for="validationServer05" class="form-label">Zip</label> <input
                            type="text" class="form-control is-invalid" id="validationServer05" required="">
                        <div class="invalid-feedback"> Please provide a valid zip.</div>
                    </div>
                    <div class="col-12">
                        <div class="form-check"> <input class="form-check-input is-invalid" type="checkbox" value=""
                                id="invalidCheck3" required=""> <label class="form-check-label" for="invalidCheck3">
                                Agree to terms and conditions </label>
                            <div class="invalid-feedback"> You must agree before submitting.</div>
                        </div>
                    </div>
                    <div class="col-12"> <button class="btn btn-primary" type="submit">Submit form</button></div>
                </form>
            </div>
        </div>
    </article>
</section>

```