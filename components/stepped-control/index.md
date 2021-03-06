---
layout: page
parent: "Components"
title: "Stepped Control"
intro: ""
jump_menu: true
title_label: 'May Require JavaScript'
---

<div class="ds-preview">
  <div class="fsa-stepped-control">
    <div class="fsa-stepped-control__bd">
      <div class="fsa-stepped-control__message" role="status">
        <strong>Optional</strong> status message
      </div>
      <div class="fsa-stepped-control__list">
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[ secondary ]</button>
        </div>
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
            <span class="fsa-stepped-control__btn-label">[ primary ]</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</div>

## Variations and Examples

### Default

<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[secondary]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[primary]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Default, with Status Message
<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__message" role="status">
      <strong>5</strong> of <strong>10</strong> Commodities are complete
    </div>
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[secondary]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[primary]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Default, with multiple secondary

<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[secondary_1]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[secondary_2]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[primary]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Directional

<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[progressive]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Directional, with multiple actions

<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[progessive_secondary]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[progressive]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Directional, with Status Message

<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__message fsa-stepped-control__message--block" role="status">
      <strong>5</strong> of <strong>10</strong> Commodities are complete
    </div>
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[progressive]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Directional, with Status Message <em>and</em> multiple actions

<div class="fsa-stepped-control">
  <div class="fsa-stepped-control__bd">
    <div class="fsa-stepped-control__message fsa-stepped-control__message--block" role="status">
      <strong>5</strong> of <strong>10</strong> Commodities are complete
    </div>
    <div class="fsa-stepped-control__list">
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive_1]</button>
      </div>
      <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
        <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive_2]</button>
      </div>
      <div class="fsa-stepped-control__item">
        <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
          <span class="fsa-stepped-control__btn-label">[progressive]</span>
        </button>
      </div>
    </div>
  </div>
</div>

### Sticky + Default

<div class="DEMO-STICKY-STEPPED-CONTROL">
  <p>This <code>&lt;div class="DEMO-STICKY-STEPPED-CONTROL"&gt;</code> container provides the <strong>boundary</strong> by which the <code>fsa-stepped-control<strong>--sticky</strong></code> variation determines when to stick.</p>
  <p>Consectetur sit dolorum iste doloribus laudantium eaque itaque unde ipsa. Tempora non accusamus nihil aut, perferendis nesciunt earum dolor laborum necessitatibus reprehenderit.</p>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio dolores, unde aperiam, nemo harum sed repellendus veniam voluptas cupiditate porro facilis voluptates ipsam, sapiente illum odit possimus debitis est. Necessitatibus.</p>
  <p>Ducimus architecto ipsa iusto aliquid deserunt commodi dolore, magnam cumque dolorum modi placeat nulla ea veniam suscipit, dolorem voluptas consequuntur repellendus non.</p>
  <div class="fsa-stepped-control fsa-stepped-control--sticky">
    <div class="fsa-stepped-control__bd">
      <div class="fsa-stepped-control__list">
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[secondary]</button>
        </div>
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
            <span class="fsa-stepped-control__btn-label">[primary]</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</div>

### Sticky + Default, with Status Message

<div class="DEMO-STICKY-STEPPED-CONTROL">
  <p>This <code>&lt;div class="DEMO-STICKY-STEPPED-CONTROL"&gt;</code> container provides the <strong>boundary</strong> by which the <code>fsa-stepped-control<strong>--sticky</strong></code> variation determines when to stick.</p>
  <p>Consectetur sit dolorum iste doloribus laudantium eaque itaque unde ipsa. Tempora non accusamus nihil aut, perferendis nesciunt earum dolor laborum necessitatibus reprehenderit.</p>
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio dolores, unde aperiam, nemo harum sed repellendus veniam voluptas cupiditate porro facilis voluptates ipsam, sapiente illum odit possimus debitis est. Necessitatibus.</p>
  <p>Ducimus architecto ipsa iusto aliquid deserunt commodi dolore, magnam cumque dolorum modi placeat nulla ea veniam suscipit, dolorem voluptas consequuntur repellendus non.</p>
  <div class="fsa-stepped-control fsa-stepped-control--sticky">
    <div class="fsa-stepped-control__bd">
      <div class="fsa-stepped-control__message" role="status">
        <strong>5</strong> of <strong>10</strong> Commodities are complete
      </div>
      <div class="fsa-stepped-control__list">
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[secondary]</button>
        </div>
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
            <span class="fsa-stepped-control__btn-label">[primary]</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</div>

### Sticky + Directional

<div class="DEMO-STICKY-STEPPED-CONTROL">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio dolores, unde aperiam, nemo harum sed repellendus veniam voluptas cupiditate porro facilis voluptates ipsam, sapiente illum odit possimus debitis est. Necessitatibus.</p>
  <p>Ducimus architecto ipsa iusto aliquid deserunt commodi dolore, magnam cumque dolorum modi placeat nulla ea veniam suscipit, dolorem voluptas consequuntur repellendus non.</p>
  <p>Reprehenderit inv omnis saepe quam assumenda iste eum cum magnamentore eos explicabo fugiat excepturi dolorum, natus deleniti? Hic magni facilis.</p>
  <p>Quia quos cupiditate quae sed earum doloribus voluptatum praesentium! Quae sapiente ea quia veniam, cumque, beatae animi commodi, molestias, temporibus rerum harum.</p>
  <div class="fsa-stepped-control fsa-stepped-control--sticky">
    <div class="fsa-stepped-control__bd">
      <div class="fsa-stepped-control__list">
        <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
          <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive]</button>
        </div>
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
            <span class="fsa-stepped-control__btn-label">[progressive]</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</div>

### Sticky + Directional, with Status Message

<div class="DEMO-STICKY-STEPPED-CONTROL">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio dolores, unde aperiam, nemo harum sed repellendus veniam voluptas cupiditate porro facilis voluptates ipsam, sapiente illum odit possimus debitis est. Necessitatibus.</p>
  <p>Ducimus architecto ipsa iusto aliquid deserunt commodi dolore, magnam cumque dolorum modi placeat nulla ea veniam suscipit, dolorem voluptas consequuntur repellendus non.</p>
  <div class="fsa-stepped-control fsa-stepped-control--sticky">
    <div class="fsa-stepped-control__bd">
      <div class="fsa-stepped-control__message fsa-stepped-control__message--block" role="status">
        <strong>5</strong> of <strong>10</strong> Commodities are complete
      </div>
      <div class="fsa-stepped-control__list">
        <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
          <button class="fsa-btn fsa-btn--alt fsa-btn--large fsa-stepped-control__btn" type="button">[regressive]</button>
        </div>
        <div class="fsa-stepped-control__item">
          <button class="fsa-btn fsa-btn--primary fsa-btn--large fsa-stepped-control__btn" type="submit">
            <span class="fsa-stepped-control__btn-label">[progressive]</span>
          </button>
        </div>
      </div>
    </div>
  </div>
</div>

### Within Modal

<p>
  <span class="fsa-m-r--s">Examples:</span>
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-stepped-control-demo-1" aria-expanded="false" type="button">Default</button>
  <button class="fsa-btn fsa-btn--secondary" data-behavior="open-modal" aria-controls="UNIQUE-ID-stepped-control-demo-2" aria-expanded="false" type="button">Directional</button>
</p>


## Usage

### Use When

* The process flow of a User requires multiple steps to perform actions
* A process flow would be enriched by a sticky control at the bottom of the screen
* A Status Message would help to gain context for the User during a stepped process

### Don't Use

* As the component to control a singular form or action
* Buttons with the visual style of a text link
* At the top of a screen as a means for navigation
* As a substitute for pagination

## General Guidance

* The Stepped Control is used as the standard Component to advance from screen to screen within an application 
* In most cases, the Stepped Control with sticky variation should be used, as it keeps the navigation controls on the screen for the User
* Variations of the Stepped Control should be used to enhance the User Experience by providing additional context that might be missing for the User.

## JavaScript Guidance

{% include scripts.about.html %}

### Summary

The JavaScript for the Sticky Stepped Control performs a number of calculations based on the position of the component in relation to the top of the screen. JavaScript is not required for the non-sticky variations of the Stepped Control component. The Component Update Events list below should trigger the change of the Sticky variant of the component.

### Component Update

* Calculate Component position, relative to bottom of screen
* Apply `fsa-stepped-control--unstuck` class to pin component

### Component Update Events

* Window scrolling
* `DOMContentLoaded`
* Window resize
* All Modals scrolling, if using Modal variant

<div tabindex="0" id="UNIQUE-ID-stepped-control-demo-1" class="fsa-modal" role="dialog" aria-hidden="true">
    <div class="fsa-modal__dialog">
      <div class="fsa-modal__content">
        <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
        <h1 class="fsa-modal__title">Modal Title</h1>
        <p>Voluptas vel, excepturi! Quo, veritatis. Aliquam voluptate, aut voluptates neque, repellat, dolore autem provident, deserunt ducimus quibusdam similique dolorum facilis. Quis, ducimus.</p>
        <p>Cupiditate, nemo illo. Rerum dolor suscipit, doloribus nam unde, nostrum quod voluptatum, amet nulla molestias debitis, officia asperiores temporibus aliquid! Ipsum, at.</p>
        <p>Maxime repellat expedita, rem, sapiente, debitis consectetur placeat dolorum deleniti delectus tenetur commodi? Optio, sequi. Fugiat, hic incidunt, vitae aspernatur voluptates molestiae?</p>
        <p>Voluptas vel, excepturi! Quo, veritatis. Aliquam voluptate, aut voluptates neque, repellat, dolore autem provident, deserunt ducimus quibusdam similique dolorum facilis. Quis, ducimus.</p>
        <p>Cupiditate, nemo illo. Rerum dolor suscipit, doloribus nam unde, nostrum quod voluptatum, amet nulla molestias debitis, officia asperiores temporibus aliquid! Ipsum, at.</p>
        <p>Maxime repellat expedita, rem, sapiente, debitis consectetur placeat dolorum deleniti delectus tenetur commodi? Optio, sequi. Fugiat, hic incidunt, vitae aspernatur voluptates molestiae?</p>
        <div class="fsa-stepped-control fsa-stepped-control--modal fsa-stepped-control--sticky fsa-stepped-control--unstuck">
          <div class="fsa-stepped-control__bd">
            <div class="fsa-stepped-control__message" role="status">
              [ status message ]
            </div>
            <div class="fsa-stepped-control__list">
              <div class="fsa-stepped-control__item">
                <button class="fsa-btn fsa-btn--alt fsa-stepped-control__btn" type="button">[ secondary ]</button>
              </div>
              <div class="fsa-stepped-control__item">
                <button class="fsa-btn fsa-btn--primary fsa-stepped-control__btn" type="submit">
                  <span class="fsa-stepped-control__btn-label">[ primary ]</span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div tabindex="0" id="UNIQUE-ID-stepped-control-demo-2" class="fsa-modal" role="dialog" aria-hidden="true">
    <div class="fsa-modal__dialog">
      <div class="fsa-modal__content">
        <button class="fsa-modal__close" data-behavior="close-modal"><img class="fsa-modal__close-icon" src="{{ site.baseurl }}img/close.svg" alt="close"></button>
        <h1 class="fsa-modal__title">Modal Title</h1>
        <p>Voluptas vel, excepturi! Quo, veritatis. Aliquam voluptate, aut voluptates neque, repellat, dolore autem provident, deserunt ducimus quibusdam similique dolorum facilis. Quis, ducimus.</p>
        <p>Cupiditate, nemo illo. Rerum dolor suscipit, doloribus nam unde, nostrum quod voluptatum, amet nulla molestias debitis, officia asperiores temporibus aliquid! Ipsum, at.</p>
        <p>Maxime repellat expedita, rem, sapiente, debitis consectetur placeat dolorum deleniti delectus tenetur commodi? Optio, sequi. Fugiat, hic incidunt, vitae aspernatur voluptates molestiae?</p>
        <p>Voluptas vel, excepturi! Quo, veritatis. Aliquam voluptate, aut voluptates neque, repellat, dolore autem provident, deserunt ducimus quibusdam similique dolorum facilis. Quis, ducimus.</p>
        <p>Cupiditate, nemo illo. Rerum dolor suscipit, doloribus nam unde, nostrum quod voluptatum, amet nulla molestias debitis, officia asperiores temporibus aliquid! Ipsum, at.</p>
        <p>Maxime repellat expedita, rem, sapiente, debitis consectetur placeat dolorum deleniti delectus tenetur commodi? Optio, sequi. Fugiat, hic incidunt, vitae aspernatur voluptates molestiae?</p>
        <div class="fsa-stepped-control fsa-stepped-control--modal fsa-stepped-control--sticky fsa-stepped-control--unstuck">
          <div class="fsa-stepped-control__bd">
            <div class="fsa-stepped-control__list">
              <div class="fsa-stepped-control__item fsa-stepped-control__item--pull">
                <button class="fsa-btn fsa-btn--alt fsa-stepped-control__btn" type="button">[ regressive ]</button>
              </div>
              <div class="fsa-stepped-control__item">
                <button class="fsa-btn fsa-btn--primary fsa-stepped-control__btn" type="submit">
                  <span class="fsa-stepped-control__btn-label">[ progressive ]</span>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>