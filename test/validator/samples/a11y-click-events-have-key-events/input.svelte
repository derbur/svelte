<script>
  export let handleKeyDown, handleKeyUp, handleKeyPress;
</script>

<div onClick={() => {}} onKeyDown={handleKeyDown}>onKeyDown is a valid handler option</div>
<div onClick={() => {}} onKeyUp={handleKeyUp}>onKeyUp is a valid handler option</div>
<div onClick={() => {}} onKeyPress={handleKeyPress}>onKeyPress is a valid handler option</div>
<div role="presentation" onClick={() => {}}>Presentation role is hidden from screen readers</div>
<div role="none" onClick={() => {}}>None is an alias for presentation</div>

<div onClick={() => {}} />

<details onClick={() => {}}>
  This is a details block
</details>
