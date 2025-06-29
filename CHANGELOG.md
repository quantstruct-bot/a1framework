<Update label="2025-06-10" description="Recent codebase updates">
  ## Framework Changes

  * Fixed a typo in port configuration ([f3e2ad8](https://github.com/a1baseai/a1framework/commit/f3e2ad888eeb346f492f968da8cbbb1043de6bb2))
    - Corrected a typographical error in the port configuration to ensure the application starts with the intended port value. This improves deployment reliability and reduces configuration errors.

  * Updated color handling logic ([1591755](https://github.com/a1baseai/a1framework/commit/1591755d0491027bce3e36b0d9392682cbbedf3c))
    - Refined or fixed the color handling in the codebase. Developers should check any UI or logging output that depends on color configuration to ensure expected results.

  * Fixed production deployment: now uses Dockerfile for Socket.IO support ([65036e8](https://github.com/a1baseai/a1framework/commit/65036e83991ecf2ba7aedfe77fcdcd1a0c7bdfac))
    - Updated deployment strategy to use a Dockerfile that explicitly supports Socket.IO, improving containerized deployments and real-time feature stability in production environments. All production deployments should now use the new Dockerfile.

  <Note>
    No API changes were introduced in these commits. Deployment processes and configuration may be affected by the Dockerfile update.
  </Note>
</Update>
