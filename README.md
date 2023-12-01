# Unity MonoBehavior Message Completions

This package provides sublime completions for UnityEngine's MonoBehavior class, e.g. OnTriggerEnter, OnTriggerExit, etc. The completions are not context aware so they "complete" anytime the completion text matches the name of the message.

These completions are necessary even with LSP-OmniSharp since MonoBehavior messages aren't part of the completion criteria as messages aren't methods that can be overridden.
