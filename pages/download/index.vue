<template>
  <div
    class="min-h-screen text-gray-900 bg-gray-100 dark:text-gray-200 dark:bg-gray-900"
  >
    <div
      class="flex flex-col min-h-screen p-12 text-gray-900 bg-gray-100 place-content-center md:items-center dark:bg-gray-900 dark:text-gray-100"
    >
      <h1 class="text-4xl">Pick your flavor of Ultramarine</h1>
      <h2 class="pt-1 text-gray-400">Latest Release: 36 (Rhode Island)</h2>
      <div class="">
        <div class="grid grid-flow-row-dense grid-cols-1 gap-10 pt-12 md:grid-cols-2 md:flex-row">
          <DownloadSection
            editionName="Flagship"
            screenshot="ultramarine.png"
            description="The flagship edition with the latest and greatest software and ourbest polish. Powered by Solus' Budgie Desktop. (Recommended)"
          />

          <DownloadSection
            editionName="GNOME"
            screenshot="GNOME.png"
            description="GNOME is a simple, elegant, and intuitive desktop environment with a focus on productivity."
          />

          <DownloadSection
            editionName="Pantheon"
            screenshot="pantheon.png"
            description="The default desktop of elementary OS focused on elegance and visual appeal."
          />

          <DownloadSection
            editionName="Cutefish"
            screenshot="cutefish.png"
            description="Simplicity, beauty, and practicality, with a familiar look. (In early development, only recommended for more advanced users)"
          />

          <DownloadSection
            editionName="Lapis"
            screenshot="ultramarine.png"
            description="The Flagship Edition, but immutable. Powered by OSTree."
            isoLink="https://lapis.ultramarine-linux.org/pub/ultramarine/36/Lapis/x86_64/iso/Ultramarine-36-20220519.0-Lapis-x86_64-ostree1.iso"
          />
        </div>
      </div>

      <h2 class="text-3xl mt-20">Torrents</h2>
      <h2 class="pt-1 text-gray-400 pb-12">You can also download Ultramarine Builds using Torrent clients from FOSS Torrents which are available
          <a class="text-gray-800 dark:text-gray-100 hover:text-blue-600 dark:hover:text-blue-200"
            href="https://fosstorrents.com/distributions/ultramarine-linux/">
              here
            </a>.
      </h2>

    </div>
  </div>

</template>
