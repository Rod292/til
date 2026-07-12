# macOS : débloquer un binaire téléchargé

`xattr -d com.apple.quarantine ./binaire` retire la mise en quarantaine Gatekeeper.
