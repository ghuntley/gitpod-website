<script lang="ts">
  export let height: number = 24;
  export let width: number = 24;
  export let title: string = "";
  export let renderedOn: "desktop" | "mobile";
</script>

<svg
  viewBox="0 0 24 24"
  {height}
  {width}
  fill="none"
  xmlns="http://www.w3.org/2000/svg"
>
  {#if title}
    {title}
  {/if}
  <g clip-path="url(#clip0-textless-renderedOn)">
    <path
      fill-rule="evenodd"
      clip-rule="evenodd"
      d="M14.07 1.195a2.364 2.364 0 01-.887 3.236l-7.11 4.04a.6.6 0 00-.304.52v6.343a.6.6 0 00.304.52l5.628 3.199a.605.605 0 00.598 0l5.628-3.198a.6.6 0 00.304-.521V11.39l-5.06 2.838a2.392 2.392 0 01-3.248-.9 2.364 2.364 0 01.905-3.23l7.239-4.062C20.272 4.8 23 6.383 23 8.901v6.914c0 1.62-.873 3.115-2.287 3.919l-6.461 3.671a4.56 4.56 0 01-4.504 0l-6.461-3.671A4.509 4.509 0 011 15.815V8.51c0-1.62.873-3.115 2.287-3.918l7.53-4.28a2.392 2.392 0 013.253.883z"
      fill="url(#paint0_linear-textless={renderedOn})"
    />
  </g>
  <defs>
    <linearGradient
      id="paint0_linear-textless={renderedOn}"
      x1="17.558"
      y1="3.629"
      x2="6.356"
      y2="21.34"
      gradientUnits="userSpaceOnUse"
    >
      <stop stop-color="#FFB45B" />
      <stop offset="1" stop-color="#FF8A00" />
    </linearGradient>
    <clipPath id="clip0-textless-renderedOn">
      <path fill="#fff" d="M0 0h24v24H0z" />
    </clipPath>
  </defs>
</svg>
