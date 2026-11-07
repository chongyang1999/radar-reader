# radar-reader

A reading and picking page for the private `daily_news` repository. It holds **no data**: when opened, it reads that day's briefing and deep-report issues with a fine-grained token kept in the browser, and writes ticks (issue body checkboxes) and comments back to the same issues. Everything downstream (sync, classification, archive) is unchanged.

Token: fine-grained, only `daily_news`, Repository permissions → Issues: Read and write.
