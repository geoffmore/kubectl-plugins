Several possibly useful plugins to the kubectl cli

Directory Layout:
~~~
.
├── bin - plugins (mostly golang) that require compilation
└── script - plugins (mostly bash) that do not require compilation
    ├── kubectl-chctx - Changes your current context
    ├── kubectl-chns - Changes the namespace of the current context. Or Doesn't,
    if that's what you want
    ├── kubectl-lspods - lists pods on the cluster in form "ns:pod:phase"
    └── kubectl-swiss - Runs an interactive pod within the current context
~~~
