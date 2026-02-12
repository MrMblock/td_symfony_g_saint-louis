# Seulement les catégories                                                                                                                                                          
  php bin/console doctrine:fixtures:load --group=category
                                                                                                                                                                                      
  # Seulement les posts                                                         
  php bin/console doctrine:fixtures:load --group=post

  # Tout (comme avant)
  php bin/console doctrine:fixtures:load
