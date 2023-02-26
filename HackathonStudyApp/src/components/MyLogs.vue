<template>
    <WelcomeItem>
      <template #icon>
        <DocumentationIcon />
      </template>
      <template #heading>Documentation</template>
      Insert text
    </WelcomeItem>
  
    <WelcomeItem>
      <template #icon>
        <ToolingIcon />
      </template>
      <template #heading>Tooling</template>
      Hey!
      <br />
      Join us!
    </WelcomeItem>
  
    <WelcomeItem>
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Ecosystem</template>
      Add text here.
    </WelcomeItem>
  
    <WelcomeItem>
      <template #icon>
        <CommunityIcon />
      </template>
      <template #heading>Community</template>
      stackoverflow
    </WelcomeItem>
  
    <WelcomeItem>
      <template #icon>
        <SupportIcon />
      </template>
      <template #heading>Support Vue</template>
      collab
    </WelcomeItem>
  </template>