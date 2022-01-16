
# SpringFactoriesLoader
    // 这个缓存中会将所有spring.factories文件中找到的类记录下来，用于之后的加载
    static final Map<ClassLoader, Map<String, List<String>>> cache = new ConcurrentReferenceHashMap<>();